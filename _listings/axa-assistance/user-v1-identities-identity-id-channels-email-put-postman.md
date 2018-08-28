{
  "info": {
    "name": "AXA Assistance Update channel",
    "_postman_id": "d14efa6e-7a63-4000-9093-3b7e30687c5d",
    "description": "Update channel",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "insurance",
      "item": [
        {
          "id": "b3b457c0-bcd4-4e0d-a146-c50ec028ead0",
          "name": "putUserV1IdentitiesIdentity_idChannelsEmail",
          "request": {
            "url": {
              "protocol": "http",
              "host": "sandbox.api.axa-assistance.com",
              "path": [
                "user/v1/identities/:identity_id/channels/email"
              ],
              "variable": [
                {
                  "id": "identity_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Update channel"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "750642a8-d83a-495e-bdec-94bb113d2c78"
            }
          ]
        }
      ]
    }
  ]
}