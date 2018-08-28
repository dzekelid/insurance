{
  "info": {
    "name": "AXA Assistance Get channel",
    "_postman_id": "210eb391-df09-422b-9343-27b04466ed5c",
    "description": "Get channel",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "insurance",
      "item": [
        {
          "id": "3316e21c-d60a-4d17-b238-48c7e47b2105",
          "name": "getUserV1IdentitiesIdentity_idChannelsSms",
          "request": {
            "url": {
              "protocol": "http",
              "host": "sandbox.api.axa-assistance.com",
              "path": [
                "user/v1/identities/:identity_id/channels/sms"
              ],
              "variable": [
                {
                  "id": "identity_id",
                  "value": "identity_id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get channel"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4b13b622-5a05-4cfa-9374-45c536362143"
            }
          ]
        }
      ]
    }
  ]
}