{
  "info": {
    "name": "AXA Assistance Provide basic details about the current deployed version of the information API",
    "_postman_id": "1b872cb2-2561-4c18-add4-4a8085a99684",
    "description": "Provide basic details about the current deployed version of the information API",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "insurance",
      "item": [
        {
          "id": "203e753d-b0a8-4640-b03a-4593ae6def04",
          "name": "getInformationVersion",
          "request": {
            "url": "http://sandbox.api.axa-assistance.com/information/version",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Provide basic details about the current deployed version of the information API"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "54d0d865-8763-4996-aca6-d231c89aee42"
            }
          ]
        }
      ]
    }
  ]
}