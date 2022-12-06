# git-game
Un xogo de pistas

## A palabra máxica
Para saber cal é a túa palabra máxica executa este comando sobre o ficheiro palabras.csv
```
cat palabras.csv | grep o_teu_nif_con_letra_maiúscula | cut -d';' -f9
```
