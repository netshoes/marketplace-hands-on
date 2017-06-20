POST http://api-sandbox.netshoes.com.br/api/v2/products/exercicio-handson/stocks

Headers:
* content-type: application/json
* client_id: ${client_id}
* access_token: ${access_token}

Payload:
```json
{
  "available": -5
}
```

```bash
curl -X POST \
  http://api-sandbox.netshoes.com.br/api/v2/products/exercicio-handson/stocks \
  -H 'access_token: ${access_token}' \
  -H 'client_id: ${client_id}' \
  -H 'content-type: application/json' \
  -d '{
  "available": -5
}'
```