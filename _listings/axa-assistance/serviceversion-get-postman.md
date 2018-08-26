{
  "info": {
    "name": "AXA Assistance Provide basic details about the current deployed version of the service API",
    "_postman_id": "6f7d2848-7d77-4d12-83a0-d352b2ac44b9",
    "description": "Provide basic details about the current deployed version of the service API",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "insurance",
      "item": [
        {
          "id": "6f871ec0-59e7-4693-a997-b907fe5374f0",
          "name": "getServiceVersion",
          "request": {
            "url": "http://sandbox.api.axa-assistance.com/service/version",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Provide basic details about the current deployed version of the service API"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a6f7f2e7-217b-48d4-ab7a-5a502d8d58bf"
            }
          ]
        }
      ]
    }
  ]
}