{
  "info": {
    "name": "Healthcare.gov Get API Topics Media Type Extension",
    "_postman_id": "e10c8e6a-b360-4718-ad8b-6e6af8714507",
    "description": "Returns pages content.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "insurance",
      "item": [
        {
          "id": "ba36c2d2-a9a1-4c8b-896e-bbc7f553139b",
          "name": "returns-pages-content",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.healthcare.gov",
              "path": [
                "api/topics:mediaTypeExtension"
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
              "id": "fd0c44d4-77f5-48e7-a864-144e259663a3"
            }
          ]
        }
      ]
    }
  ]
}