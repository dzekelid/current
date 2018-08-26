{
  "info": {
    "name": "Dezrez Sends alerts for all current platform issues.",
    "_postman_id": "3c8bfe3d-8e8b-4320-90dc-5b0ad7113b6c",
    "description": "Sends alerts for all current platform issues..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Sends",
      "item": [
        {
          "id": "f36126c8-db74-4926-8270-06dd8a0f42be",
          "name": "CorePlatformState_SendPendingAlerts",
          "request": {
            "url": "http://api.dezrez.com/api/coreplatformstate/sendpendingalerts",
            "method": "POST",
            "header": [
              {
                "key": "Rezi-Api-Version",
                "value": "{}",
                "description": "Specifies which version of the API to call",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Sends alerts for all current platform issues.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "00f6ccdb-473f-4183-8c81-662b5693fb0f"
            }
          ]
        }
      ]
    }
  ]
}