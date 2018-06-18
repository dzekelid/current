{
  "info": {
    "name": "AXA Assistance Provide basic details about the current deployed version of the User API",
    "_postman_id": "abf54943-a3e8-4023-bf66-0f5adc1fb3e0",
    "description": "Provide basic details about the current deployed version of the User API",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "insurance",
      "item": [
        {
          "id": "7b0d788c-0ef1-4499-980b-5a4c5e5e5966",
          "name": "getUserVersion",
          "request": {
            "url": "http://sandbox.api.axa-assistance.com/user/version",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Provide basic details about the current deployed version of the User API"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9e0ca2c6-7060-4c08-8e4b-c88cc8759480"
            }
          ]
        }
      ]
    }
  ]
}