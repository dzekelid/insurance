{
  "info": {
    "name": "BetterDoctor Retrieve insurance providers and plans",
    "_postman_id": "aaf386d6-48a6-4b3b-937d-24c8eba0fc77",
    "description": "Insurance provider & plan list",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "insurance",
      "item": [
        {
          "id": "3b9d8997-6848-4eb3-9d74-2a5a0ddcecd5",
          "name": "insurance-provider--plan-list",
          "request": {
            "url": "http://api.betterdoctor.com/2016-03-01/insurances?fields=%7B%7D&limit=%7B%7D&skip=%7B%7D&user_key=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Insurance provider & plan list"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e74bec36-3413-41df-ad88-3d3397775189"
            }
          ]
        }
      ]
    }
  ]
}