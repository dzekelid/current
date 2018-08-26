{
  "info": {
    "name": "Santander Bank Get Current Business Accounts",
    "_postman_id": "744ffff3-0601-4ba1-b8f1-489a5e3e14fc",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple BCA products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Current",
      "item": [
        {
          "id": "2cefdf51-f5fa-40b3-a17f-57c97c7aec3b",
          "name": "getCurentBusinessAccounts",
          "request": {
            "url": "http://openapi.santander.co.uk/open-banking/v2.1/business-current-accounts/",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple BCA products."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8ff7b5d8-bb87-4870-a447-0d2d7a1f023d"
            }
          ]
        }
      ]
    }
  ]
}