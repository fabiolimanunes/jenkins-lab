Teste Integração com o Jenkins
# Comandos úteis
Saber qual rede devemos configurar o metal-lb no cluster kind

`docker network inspect kind | jq -r '.[].IPAM.Config[0].Subnet'`

