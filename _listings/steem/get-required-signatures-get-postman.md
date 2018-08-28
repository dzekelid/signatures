{
  "info": {
    "name": "Steem get_required_signatures",
    "_postman_id": "206d47cb-c4f2-454d-86f3-d39d75616a37",
    "description": "get_required_signatures",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Get",
      "item": [
        {
          "id": "4dfa6596-8cc4-4e69-9289-94953ea52603",
          "name": "get-required-signatures",
          "request": {
            "url": "http://api.steemjs.com/get_required_signatures?availableKeys=%7B%7D&trx=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get_required_signatures"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e765cfb3-360c-4f7f-a42e-e46b53adf9a0"
            }
          ]
        }
      ]
    }
  ]
}