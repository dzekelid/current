{
  "info": {
    "name": "Lloyds Bank Get Current Business Accounts",
    "_postman_id": "dbb3564d-b9cf-4c42-91e5-ed618c0807c0",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple BCA products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Business",
      "item": [
        {
          "id": "a64093d9-9912-41e4-aafe-37909b6c5aa0",
          "name": "getCurentBusinessAccounts",
          "request": {
            "url": "http://api.lloydsbank.com/open-banking/v2.1/business-current-accounts/",
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
              "id": "e9900f75-22a4-41c1-852e-2e3b8d0d4e8b"
            }
          ]
        }
      ]
    }
  ]
}