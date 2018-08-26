{
  "info": {
    "name": "AXA Assistance Provide basic details about the current deployed version of the sales API",
    "_postman_id": "ba3c50e1-8a09-4963-92a2-549890159287",
    "description": "Provide basic details about the current deployed version of the sales API",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "insurance",
      "item": [
        {
          "id": "7dc43b9a-e68f-4231-b08b-f6fc6cd5c267",
          "name": "getSalesVersion",
          "request": {
            "url": "http://sandbox.api.axa-assistance.com/sales/version",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Provide basic details about the current deployed version of the sales API"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dc5db48a-de69-4bfb-98e9-734b570be06e"
            }
          ]
        }
      ]
    }
  ]
}