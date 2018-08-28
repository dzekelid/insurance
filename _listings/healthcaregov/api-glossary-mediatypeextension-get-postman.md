{
  "info": {
    "name": "Healthcare.gov Get API Glossary Media Type Extension",
    "_postman_id": "f0f7e621-53fb-4d39-ad3f-a19227ed15fb",
    "description": "Returns pages content.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "insurance",
      "item": [
        {
          "id": "4e220fc0-2488-407b-8612-6a311c39b72f",
          "name": "returns-pages-content",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.healthcare.gov",
              "path": [
                "api/glossary:mediaTypeExtension"
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
              "id": "5da7d605-33ba-4962-82e0-b21f3cc390aa"
            }
          ]
        }
      ]
    }
  ]
}