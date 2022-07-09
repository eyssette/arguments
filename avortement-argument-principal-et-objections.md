%%{init: {"theme":"base","themeCSS": "#Argument rect{stroke:transparent; fill:#e5e5e5} #Argument span {color:transparent} .edgeLabel{color:#888; font-size:0.9em; margin-right:3px} .edgeLabel i{color:crimson} .edge-pattern-dotted{stroke:crimson} .edge-pattern-solid{stroke:green} #flowchart-pointEnd{fill:green}  g[id*=\"O\"] *{stroke:crimson!important; font-size:0.95em} circle+g span{color:white; } circle{fill:green!important} g[id*=\"C\"] * {fill:black;color:white;font-weight:bold}  g[id*=\"V\"] * {stroke:transparent; fill:transparent; color:transparent} .edge-thickness-thick{stroke:transparent}","themeVariables":{"secondaryColor":"transparent","primaryColor":"white","primaryBorderColor":"black"},"flowchart":{"htmlLabels":true, "padding":20, "rankSpacing":20, "nodeSpacing":20}} }%%
flowchart TB
    %%accTitle: Titre
    %%accDescr: Description
    subgraph Argument
    direction TB
    %% 1("Prémisse")
    %% Pour utiliser les guillemets dans une prémisse : #quot;
    %% 1 -->|Par conséquent|2
    %% 1 & 2 --- PL1((&))
    %% C(["Conclusion"])
    1("(1) Un embryon <br>ou un fœtus est<br> une personne")
    2("(2) Toute <br>personne a<br> droit à la vie")
    1 & 2 --- PL1((&))
    PL1 --- 3
    3("(3) Un embryon <br>ou un fœtus a <br>droit à la vie")

    V1 ==== 3

    1.2("(1') Un embryon <br>ou un fœtus est un <br> individu qui peut <br>devenir une personne")
    2.2("(2') Tout individu<br> qui peut devenir <br>une personne a <br>droit à la vie")
    1.2 & 2.2 --- PL1.2((&))
    PL1.2 --- 3


    4["(4) Si un être a droit à la vie, alors <br>tout acte qui a pour conséquence <br> d'interrompre la vie de cet être<br> est moralement inacceptable"]

    3 & 4 --- PL2((&))
    PL2 --- 5

    5["(5) Tout acte qui a pour conséquence <br> d'interrompre la vie d'un embryon ou <br>d'un fœtus est moralement inacceptable"]

    6["(6) L'avortement a pour conséquence <br>d'interrompre la vie d'un<br> embryon ou d'un fœtus "]

    5 & 6 --- PL3((&))
    V2 === PL3
    PL3 --- 7
    
    7["(7) L'avortement est <br>moralement inacceptable"]

    8["(8) Si un acte est moralement<br>inacceptable, alors il est<br> légitime de l'interdire légalement"]

    7 & 8 --- PL4((&))
    PL4 --- C

    C(["Il est légitime<br>d'interdire légalement<br>l'avortement"])
    end
    %% OBJECTIONS

    O1["<b>Objection 1 :</b> <br> L'embryon n'est pas une personne<br> et le fœtus n'est une personne qu'à<br> partir du moment T où il acquiert <br>les caractéristiques C, ce qui rend<br> légitime l'avortement jusqu'au moment T"]
    O1-.-|<i>objection !</i>|1

    O2["<b>Objection 2 :</b> <br> Un individu qui peut devenir <br>une personne n'a pas le même<br> statut moral qu'une personne"]
    O2-.-|<i>objection !</i>|2.2

    O4["<b>Objection 3 :</b> <br>Ce n'est pas toujours vrai. Il y a des<br>  situations analogues où le droit à la vie<br>  des femmes prévaut, et des situations<br> où le droit des femmes à disposer de <br>leur corps prévaut (<i>cf.</i> les expériences de <br>pensée de Judith Jarvis Thompson)"]
    O4-..-|<i>objection !</i>|4

    O6["<b>Objection 4 :</b> <br> L'avortement est l'expulsion de <br>l'embryon ou du fœtus hors<br> du corps d'une femme. Si un État<br> veut empêcher l'interruption de<br>  la vie d'un embryon ou d'un fœtus,<br> alors il ne doit pas imposer l'interdiction<br>  de l'avortement, mais faire en sorte que<br>  l'embryon ou le fœtus puisse vivre après expulsion."]
    O6-..-|<i>objection !</i>|6

    O8.1["<b>Objection 5.1 :</b> <br>Objection 5.1 : L'interdiction légale<br> de l'avortement est inefficace et<br> met en danger les femmes qui iront<br> avorter de manière clandestine"]
    O8.1-..-|<i>objection !</i>|8

    O8.2["<b>Objection 5.2 :</b> <br>L'avortement est une question <br>qui relève de la morale et non de <br>la loi. On ne peut pas imposer <br>l'interdiction de l'avortement en raison <br>des conceptions morales personnelles <br>que l'on a du bien et du mal."]
    O8.2-.-|<i>objection !</i>|8

    