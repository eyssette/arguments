# Arguments

Un répertoire d'arguments philosophiques reconstruits.

## Outil utilisé

J'utilise [Mermaid](https://mermaid-js.github.io/mermaid/#/), un logiciel de création de schémas à partir d'un simple fichier texte.

J'ai créé un [modèle](https://mermaid.live/edit#pako:eNp1VO1O2zAUfZWLq6LCCOJDSCzVJo3Cj01orVS0P4Qfrn1JPRw72I6ApXkgnoMX202aNhlijVQn95x7z_2SSyasRBaz4bBURoUYyoSFJWaYsDhhC-7p5aA1TeZzskLCBt9cWmRoAjgUofTB2QeMg-PG59yRfQz3Sut4gGf1U0HnQAQDpbDaur5DBYcoU7zmC9QtOjg_P6c41oTIqz8YHx1-xmwMGXepMpFT6TLEp_lz6xnlPAR0JpKWTrnJSTiVeWvek7zVastJHSIxBvfaPokldyHKrTLhysiyqaLFIb1Vcv9LkiRsWv_dwf47lR2V5dYF3tTfz_sMswqEckLjp7RpQVvj01IFHMMG7Ol1saqe8KQVhjVzobl4GPdDNbJP2DRnYbWsuun94k7xhUZPM6QhexTWSO5eJrV7M-3ePBq3nMr6h9Bo9KEL6yS6jtAklLCKGNturuWWIdPNdGv54Aqsg3AplUnJcHJEn6T-MM-52JiqCqrhMDHbSHBzkRig33DIhbhRQWMMdDjsmS_RCxdDc6g8KGvWoC8WqeP5EjaruDZLVa8wsXrB4XiUsJl7e82Ur_d_bwvMbOGgCEorjw6ol5AWNAjqbvAgqXtQGIR84woxDB4LG8ZdZIiir6sZd0Dd92-vjwVlsjrp4btwQpwIZtfHo9HuXqc9Gd3SAlgjdOHrqthdi32c7cdKkzX431ho5FZwevHjanLzffpz3pmOyW-6-L1uGbn1kOgwWtkNBDurU3bAMnQZV5Lul7JmdlcLbO6WxFTEK3LJA15JFaxj8T3XHg8YL4KdvxjR7ktLulSc5pi1rOovbpadgw) pour pouvoir reconstruire des arguments à l'aide de Mermaid.

```mermaid
%%{init: {"theme":"base","themeCSS": "#Argument rect{stroke:transparent; fill:#e5e5e5} #Argument span {color:transparent} .edgeLabel{color:#888; font-size:0.9em; margin-right:3px} .edge-pattern-dotted{stroke:crimson} .edge-pattern-solid{stroke:green} #flowchart-pointEnd{fill:green}  g[id*=\"O\"] *{stroke:crimson!important; font-size:0.95em} circle+g span{color:white; } circle{fill:green!important} g[id*=\"C\"] * {fill:black;color:white;font-weight:bold}","themeVariables":{"secondaryColor":"transparent","primaryColor":"white","primaryBorderColor":"black"},"flowchart":{"htmlLabels":true,"padding":20,"rankSpacing":20}} }%%
flowchart TB
    subgraph Argument
    direction TB
    1("Prémisse")
    1 --->|Par conséquent|C    
    2("Prémisse")
    3("Prémisse")
    2 & 3 --- PL1((&))
    PL1 -->|Par conséquent|C
    C(["Conclusion"])
    end
    O1["Objection"]
    O1-.-|objection !|3
```

[![](https://mermaid.ink/img/pako:eNp9VNtO20AQ_ZVho6BAMYJESNRRK5XAQyvURErUF8zDxjs4W9a7ZnctShN_EN_Bj3V8S1yUNpG89pkzc-amXbPYCGQh6_fXUksfwjpifoUpRiyM2JI7ejlpoMl8TihErPfFJnmK2oPF2K-dt-YRQ2-5dhm3hI_hQSoV9vCi_BewcyCChnVslLFdhwJOUSR4y5eoGmvv8vKS4hjtAyd_Y3h2-hHTMaTcJlIHViYrH46yX41nkHHv0epAGDpFm1NsZeqMfk9yRsktJ7GIxOg9KPMcr7j1QWak9jdarKsqGjskd1Icf4qiiE3Lxz0cv1M5kGlmrOdV_d28LzAtIJY2VvghqVrQ1Pi8kh7H0Bo7ertYRUd40ghDzVwqHj-Ou6Eq2WesmrM0ShS76f3gVvKlQkczpCE7jI0W3L5MSvdq2p15VG4ZlfUXodLomq6MFWh3hCqhiBXE2Hazllv5VFXTLeW9zbEMwoWQOiFgeEafpP44z3jcQkUBRb8f6W0kWFxFGujX7_M4XkivMAQ6LHbga3SxDaE6ZOal0bXR5cvE8mwF7SrWsJDlChOrExzOBxGb2bfXVLpy_4-2hpnJLeReKunQAvUSkpwGQd31DgR1D3KNkLWuEELvKTd-vIsMQfB5M-MWqPvu7fUpp0w2w479EIbECWB2ez4YHB7ttCeDO1oAo2OVu7Iqdt_Y9mdbKu2RmtTW7nO413-0Fx1SfqM9-dEX_Efun7mjFtsCp1ffbiaLr9Pv8xqanpPTdPmzng_5tHBwGmxMi8PBZsROWIo25VLQTbYuabtLDNpbLNIF8fJMcI83QnpjWfjAlcMTxnNv5i86bjazIV1LThuT1mDxByiuvGA)](https://mermaid.live/edit#pako:eNp9VNtO20AQ_ZVho6BAMYJESNRRK5XAQyvURErUF8zDxjs4W9a7ZnctShN_EN_Bj3V8S1yUNpG89pkzc-amXbPYCGQh6_fXUksfwjpifoUpRiyM2JI7ejlpoMl8TihErPfFJnmK2oPF2K-dt-YRQ2-5dhm3hI_hQSoV9vCi_BewcyCChnVslLFdhwJOUSR4y5eoGmvv8vKS4hjtAyd_Y3h2-hHTMaTcJlIHViYrH46yX41nkHHv0epAGDpFm1NsZeqMfk9yRsktJ7GIxOg9KPMcr7j1QWak9jdarKsqGjskd1Icf4qiiE3Lxz0cv1M5kGlmrOdV_d28LzAtIJY2VvghqVrQ1Pi8kh7H0Bo7ertYRUd40ghDzVwqHj-Ou6Eq2WesmrM0ShS76f3gVvKlQkczpCE7jI0W3L5MSvdq2p15VG4ZlfUXodLomq6MFWh3hCqhiBXE2Hazllv5VFXTLeW9zbEMwoWQOiFgeEafpP44z3jcQkUBRb8f6W0kWFxFGujX7_M4XkivMAQ6LHbga3SxDaE6ZOal0bXR5cvE8mwF7SrWsJDlChOrExzOBxGb2bfXVLpy_4-2hpnJLeReKunQAvUSkpwGQd31DgR1D3KNkLWuEELvKTd-vIsMQfB5M-MWqPvu7fUpp0w2w479EIbECWB2ez4YHB7ttCeDO1oAo2OVu7Iqdt_Y9mdbKu2RmtTW7nO413-0Fx1SfqM9-dEX_Efun7mjFtsCp1ffbiaLr9Pv8xqanpPTdPmzng_5tHBwGmxMi8PBZsROWIo25VLQTbYuabtLDNpbLNIF8fJMcI83QnpjWfjAlcMTxnNv5i86bjazIV1LThuT1mDxByiuvGA)

On peut tester ce modèle dans l'outil en ligne [Mermaid - Live Editor](https://mermaid.live/edit#pako:eNp9VO1O2zAUfZWLqyJgBEErJJZqk0bhxya0ViraH8IP176kHo4dbEeMtXkgnoMX202atBnq1kpxcu6599wvecmElchi1u8vlVEhhmXCwgIzTFicsDn39HLcQOPZjFBIWO-LS4sMTQCHIix9cPYR4-C48Tl3hI_gQWkd9_C8-pewdSCCgaWw2rquQwknKFO84XPUjbV3cXFBcawJkVe_MT49-YjZCDLuUmUip9JFiIf5r8YzynkI6EwkLZ2yzUk4lXlr3pO81WrDSR0iMXoP2j6LBXchyq0y4drIZV1FY4f0TsmjT0mSsEn1uIejdyp7KsutC7yuv5v3OWYlCOWExg9p3YKmxueFCjiC1tjR28YqO8LjRhjWzLnm4nHUDVXLPmPdnLnVstxO7wd3is81epohDdmjsEZy9zKu3Otpd-ZRu-VU1l-EWqNrurROotsS6oQSVhJj08213CJkup5uJR9cgVUQLqUyKQGDU_ok9cdZzkULlSWU_X5iNpHg9jIxQL9-nwtxq4LGGOhw2IGv0AsXQ32oPChr1kZfzFPH8wW0q7iGpapWmFid4HB2kLCpe3vNlK_2_3BjmNrCQRGUVh4dUC8hLWgQ1N3gQVL3oDAIeesKMfSeChtG28gQRZ9XU-6Auu_fXp8KymQ16Nj3YUCcCKY3ZwcH-4db7fHBHS2ANUIXvqqK3Te23dlWSjukxmtr9znY6T_ciQ4ov-GO_OgL_iP3z9zRyE2Bk8tv1-Pbr5PvszU0OSOnyfznej7k08LRSbSyLQ57qyE7Zhm6jCtJN9myom0vMWhvscSUxCtyyQNeSxWsY_ED1x6PGS-Cnb0Y0WxmQ7pSnDYma1jlH-S4vKs).


La [documentation de Mermaid](https://mermaid-js.github.io/mermaid/#/flowchart) est très utile : il faut regarder la section sur les schémas de type “Flowchart”.
