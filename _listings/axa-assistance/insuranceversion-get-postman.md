{
  "info": {
    "name": "AXA Assistance Provide basic details about the current deployed version of the insurance API",
    "_postman_id": "7c0247f6-c8c4-440c-9e7c-ed11455cd1a2",
    "description": "Provide basic details about the current deployed version of the insurance API",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "insurance",
      "item": [
        {
          "id": "3bcc5e30-99c6-4df1-9ddd-e5a10885b797",
          "name": "getInsuranceVersion",
          "request": {
            "url": "http://sandbox.api.axa-assistance.com/insurance/version",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Provide basic details about the current deployed version of the insurance API"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "95a68af3-ccee-45f1-bd63-b4f56a19c14b"
            }
          ]
        }
      ]
    }
  ]
}