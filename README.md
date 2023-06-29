## Cardano Azzurra

La prima comunita' italiana di Cardano Stake Pool Operators | The first Italian community of Cardano Stake Pool Operators

https://www.cardanoazzurra.it

### Prerequisiti per l'ingresso
Per poter entrare a far parte del gruppo di SPO di Cardano Azzurra basta essere italiani ed operatori di una pool. Non e' necessario che la pool sia in Italia, ma solo che l'operatore sia italiano.

### Come richiedere l'ingresso in Cardano Azzurra
Per richiedere l'attivazione della pool nell'elenco di Cardano Azzurra e' necessario creare una pull request a questo repository aggiungendo l'id (bech32) e ticker della propria pool al file azzurra.json

Esempio:
```yaml
{"pools":[
    {"ticker":"ADATA",   "id":"pool1adhpjj009c0jekumqswj5jux6nvrw7v2k0wlu57vfjh7gd5wyh9"},
    {"ticker":"NEWPOOL", "id":"xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"},   
]}
```

