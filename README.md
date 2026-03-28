# kong

## tests

- check server is up

`curl localhost:8001/status | jq`

- run simple call

`curl localhost:8000/gerar_uuid/uuid  --header "apikey: secretw"`