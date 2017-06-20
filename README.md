POST http://api-sandbox.netshoes.com.br/api/v2/products/exercicio-handson/prices
Headers:
* content-type: application/json
* client_id: ${client_id}
* access_token: ${access_token}

```json
{
  "listPrice": 26,
  "salePrice": 110.50
}
```

```bash
curl -X POST \
  http://api-sandbox.netshoes.com.br/api/v2/products/exercicio-handson/prices \
  -H 'access_token: ${access_token}' \
  -H 'client_id: ${client_id}' \
  -H 'content-type: application/json' \
  -d '{
  "listPrice": 26,
  "salePrice": 110.50
}'
```
