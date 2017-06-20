PUT http://api-sandbox.netshoes.com.br/api/v2/products/exercicio-handson

Headers:
* content-type: application/json
* client_id: ${client_id}
* access_token: ${access_token}
```json
{
   "sku":"exercicio-handson",
   "productGroup": "exercicio-handson",
   "department": "Dia a dia",
   "productType": "Esportivo",
   "brand": "Nike",
   "name": "Tênis Priority Mid",
   "description": "O Tênis Priority Mid foi desenhado para seu dia a dia.",
   "color": "Preto",
   "gender": "Homem",
   "manufacturerCode":"exercicio-handson",
   "size": "40",
   "height": "0.15",
   "width": 1,
   "depth": 1,
   "weight": 0,
   "video":"http://www.netshoes.com",
   "images": [
      {
         "url":"http://myserver/image1.jpg"
      }
   ],
   "attributes": [
     {
         "name": "Tecnologias",
         "values": [
            "Air"
         ]
     }
   ]
}
```

```bash
curl -X PUT \
  http://api-sandbox.netshoes.com.br/api/v2/products/exercicio-handson \
  -H 'access_token: ${access_token}' \
  -H 'client_id: ${client_id}' \
  -H 'content-type: application/json' \
  -d '{
   "sku":"exercicio-handson",
   "productGroup": "exercicio-handson",
   "department": "Dia a dia",
   "productType": "Esportivo",
   "brand": "Nike",
   "name": "Tênis Priority Mid",
   "description": "O Tênis Priority Mid foi desenhado para seu dia a dia.",
   "color": "Preto",
   "gender": "Homem",
   "manufacturerCode":"exercicio-handson",
   "size": "40",
   "height": "0.15",
   "width": 1,
   "depth": 1,
   "weight": 0,
   "video":"http://www.netshoes.com",
   "images": [
      {
         "url":"http://myserver/image1.jpg"
      }
   ],
   "attributes": [
     {
         "name": "Tecnologias",
         "values": [
            "Air"
         ]
     }
   ]
}'
```