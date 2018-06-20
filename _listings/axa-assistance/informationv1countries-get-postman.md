{
  "info": {
    "name": "AXA Assistance Retrieve all countries",
    "_postman_id": "3eaed58e-1545-4256-8912-7d34f37940ec",
    "description": "Retrieve all countries",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "insurance",
      "item": [
        {
          "id": "def3ca42-b94d-4ee9-bbcf-9119674f2933",
          "name": "getInformationV1Countries",
          "request": {
            "url": "http://sandbox.api.axa-assistance.com/information/v1/countries",
            "method": "GET",
            "header": [
              {
                "key": "accept-language",
                "value": "{}",
                "description": "Language/Country",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve all countries"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9bceb4fd-17d8-42b6-96b6-571883b20ee8"
            }
          ]
        }
      ]
    }
  ]
}