{
  "info": {
    "name": "Steem get_potential_signatures",
    "_postman_id": "76870847-b45a-4619-95f8-2821c1bc8636",
    "description": "get_potential_signatures",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Get",
      "item": [
        {
          "id": "83ff0207-24b8-4f1f-83d9-43f336fc20ea",
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
              "id": "570398cf-aaa9-4848-9e17-760981890f48"
            }
          ]
        },
        {
          "id": "9189ab6e-170d-4183-b1b3-176eb55ac274",
          "name": "get-potential-signatures",
          "request": {
            "url": "http://api.steemjs.com/get_potential_signatures?trx=%7B%7D",
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
            "description": "get_potential_signatures"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d87f2a82-85b4-40f9-bcfd-5262ce11934e"
            }
          ]
        }
      ]
    }
  ]
}