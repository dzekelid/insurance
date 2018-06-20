{
  "info": {
    "name": "Healthcare.gov Get API Questions Media Type Extension",
    "_postman_id": "d4a3b0ed-6210-4eb2-8314-6e9e3737de88",
    "description": "Returns pages content.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "insurance",
      "item": [
        {
          "id": "2391c1ca-2c7e-400f-8d76-786c950fe28c",
          "name": "returns-pages-content",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.healthcare.gov",
              "path": [
                "api/questions:mediaTypeExtension"
              ],
              "variable": [
                {
                  "id": "mediaTypeExtension",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns pages content"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f590b086-3bad-4cab-a584-e5f7347e46f0"
            }
          ]
        }
      ]
    }
  ]
}