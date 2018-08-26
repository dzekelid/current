{
  "info": {
    "name": "First Trust Bank (Open Banking) Get Current Business Accounts",
    "_postman_id": "b6d0a41e-f75b-4c75-9fb1-4d4102db752b",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple BCA products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Current",
      "item": [
        {
          "id": "4ee78b67-4eb7-4942-a07b-3c5ee976c62b",
          "name": "getCurentBusinessAccounts",
          "request": {
            "url": "http://openapi.firsttrustbank.co.uk/open-banking/v2.1/business-current-accounts/",
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
              "id": "5a155dfd-3ea9-42f3-96be-c9de085e837b"
            }
          ]
        }
      ]
    }
  ]
}