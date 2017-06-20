PUT http://api-sandbox.netshoes.com.br/api/v2/products/exercicio-handson/status

Headers:
* content-type: application/json
* client_id: ${client_id}
* access_token: ${access_token}

Payload
```json
{
	"status": "OK"
}
```

```bash
curl -X PUT \
  http://api-sandbox.netshoes.com.br/api/v2/products/exercicio-handson/status \
  -H 'access_token: ${access_token}' \
  -H 'client_id: ${client_id}' \
  -H 'content-type: application/json' \
  -d '{
	"status": "OK"
}'
```
