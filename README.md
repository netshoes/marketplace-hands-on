POST http://api-sandbox.netshoes.com.br/api/v2/products

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
   "brand": "Naike",
   "name": "Tênis Naike Cor Avermelhado Masculino ou Feminino para esportes muito leve com apenas 100 gramas",
   "description": "O Tênis Priority Mid foi desenhado para seu dia a dia.",
   "color": "Preta",
   "gender": "homem",
   "manufacturerCode":"exercicio-handson",
   "size": "40",
   "height": "0,15",
   "width": 1,
   "depth": 1,
   "weight": 0,
   "video":"www.netshoes.com",
   "images": [
      {
         "url":""
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