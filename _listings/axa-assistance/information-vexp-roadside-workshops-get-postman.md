{
  "info": {
    "name": "AXA Assistance Gets list of nearest workshops.",
    "_postman_id": "95c1c541-afbf-423f-97f3-831557b901d1",
    "description": "Gets list of nearest workshops.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "insurance",
      "item": [
        {
          "id": "275e8d59-afc0-41eb-b4b2-84b009e6c036",
          "name": "getInformationVexpRoadsideWorkshops",
          "request": {
            "url": "http://sandbox.api.axa-assistance.com/information/vexp/roadside/workshops?latitude=%7B%7D&longitude=%7B%7D&radius=%7B%7D&radius_unit=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets list of nearest workshops"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "130c700d-93af-4a9f-9b27-dd922a7cbe22"
            }
          ]
        }
      ]
    }
  ]
}