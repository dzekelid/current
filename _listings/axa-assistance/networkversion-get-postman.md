{
  "info": {
    "name": "AXA Assistance Provide basic details about the current deployed version of the network API",
    "_postman_id": "6a3409a7-9d3b-466f-8ac9-6fdd180de77b",
    "description": "Provide basic details about the current deployed version of the network API",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "insurance",
      "item": [
        {
          "id": "b61bde18-cb1d-42ea-8e46-6a114d7a0fa3",
          "name": "getNetworkVersion",
          "request": {
            "url": "http://sandbox.api.axa-assistance.com/network/version",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Provide basic details about the current deployed version of the network API"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "207451ee-9f3e-408f-b5cd-58883612e223"
            }
          ]
        }
      ]
    }
  ]
}