{
  "info": {
    "name": "AXA Assistance Provide basic details about the current deployed version of the on demand API",
    "_postman_id": "96d691ac-d1de-4f4e-8f3b-9854558369f6",
    "description": "Provide basic details about the current deployed version of the on demand API",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "insurance",
      "item": [
        {
          "id": "fafde553-bdb7-484b-a6ba-6c0bac80be1f",
          "name": "getOndemandVersion",
          "request": {
            "url": "http://sandbox.api.axa-assistance.com/ondemand/version",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Provide basic details about the current deployed version of the on demand API"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "52dbaad5-2649-4471-a4fd-572f7e3d23cc"
            }
          ]
        }
      ]
    }
  ]
}