{
  "info": {
    "name": "AXA Assistance Gets the availabilities of medical providers.",
    "_postman_id": "c0fa3cad-e81c-48f3-8b7b-c8f3671750e0",
    "description": "Gets the availabilities of medical providers.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "insurance",
      "item": [
        {
          "id": "ea7c95db-50aa-4fd2-9f84-c57b8543c36e",
          "name": "getNetworkV1Medical_providersAvailabilities",
          "request": {
            "url": "http://sandbox.api.axa-assistance.com/network/v1/medical_providers/availabilities?end_date=%7B%7D&start_date=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the availabilities of medical providers"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "258f041b-c2d6-440b-91f4-4c1d5799623e"
            }
          ]
        }
      ]
    }
  ]
}