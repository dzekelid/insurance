{
  "info": {
    "name": "Healthcare.gov Get API Blog Media Type Extension",
    "_postman_id": "a0ef196a-4e94-4fe6-aaee-25b4d3f80db1",
    "description": "Returns pages content.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "insurance",
      "item": [
        {
          "id": "8d61baf1-d1d3-4cae-a00f-9d6ce1535437",
          "name": "returns-pages-content",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.healthcare.gov",
              "path": [
                "api/blog:mediaTypeExtension"
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
              "id": "a5f0a4ec-02b1-4051-904c-061c7cfb42d5"
            }
          ]
        }
      ]
    }
  ]
}