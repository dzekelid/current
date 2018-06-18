{
  "info": {
    "name": "Bank of Ireland Get Personal Current Accounts",
    "_postman_id": "528cef36-7c79-40c0-acb0-28b541b96b00",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple PCA products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Personal",
      "item": [
        {
          "id": "9fe891ba-9fbb-4777-9357-a7a4e5945d49",
          "name": "getCurrentPersonalAccounts",
          "request": {
            "url": "http://openapi.bankofireland.com/open-banking/v2.1/personal-current-accounts/",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple PCA products."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bcc25b95-2049-4e02-8a73-e21bb9e6abb0"
            }
          ]
        }
      ]
    }
  ]
}