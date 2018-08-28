{
  "info": {
    "name": "Healthcare.gov Get API States Media Type Extension",
    "_postman_id": "9fa1d995-1bde-4a48-8a7f-1ebedb0e26bb",
    "description": "Returns pages content.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "insurance",
      "item": [
        {
          "id": "2286a508-6802-42bb-b097-b9868323c60c",
          "name": "returns-pages-content",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.healthcare.gov",
              "path": [
                "api/states:mediaTypeExtension"
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
              "id": "fc71d4f7-1a9c-48fd-a387-23e2aa0a4bdb"
            }
          ]
        }
      ]
    }
  ]
}