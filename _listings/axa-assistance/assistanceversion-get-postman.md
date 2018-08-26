{
  "info": {
    "name": "AXA Assistance Provide basic details about the current deployed version of the assistance API",
    "_postman_id": "aa4d14ac-70b6-4401-a177-b5772c20b2d6",
    "description": "Provide basic details about the current deployed version of the assistance API",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "insurance",
      "item": [
        {
          "id": "08803523-3ed6-47d4-b2bb-2f8ee499d01b",
          "name": "getAssistanceVersion",
          "request": {
            "url": "http://sandbox.api.axa-assistance.com/assistance/version",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Provide basic details about the current deployed version of the assistance API"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "33c7ab5c-71a6-4bf6-9d57-4dacf40fad7a"
            }
          ]
        }
      ]
    }
  ]
}