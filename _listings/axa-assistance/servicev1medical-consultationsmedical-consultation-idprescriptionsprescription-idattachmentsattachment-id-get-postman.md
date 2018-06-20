{
  "info": {
    "name": "AXA Assistance Retrieve an attachment",
    "_postman_id": "84f33842-1d14-44bb-8f8e-608967543d12",
    "description": "Retrieve an attachment",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "insurance",
      "item": [
        {
          "id": "6c0dbf94-6daf-4065-9881-befc71678edb",
          "name": "getServiceV1Medical_consultationsMedical_consultation_idPrescriptionsPrescription_idAttachmentsAttac",
          "request": {
            "url": {
              "protocol": "http",
              "host": "sandbox.api.axa-assistance.com",
              "path": [
                "service/v1/medical_consultations/:medical_consultation_id/prescriptions/:prescription_id/attachments/:attachment_id"
              ],
              "variable": [
                {
                  "id": "attachment_id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "medical_consultation_id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "prescription_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve an attachment"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "415dd1c2-0bda-4583-87ce-5b307e3f6e02"
            }
          ]
        }
      ]
    }
  ]
}