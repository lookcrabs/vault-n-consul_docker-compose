* in consul dir run docker-compose up
* wait for consul to elect a leader
* in vault dir run docker-compose up
* wait a bit for vault to register with consul
*
* either browse to localhost:8200 or use the vault cli with VAULT_ADDR="http://localhost:8200"
* do yo thang
*
*
