{
  "info": {
    "name": "Bank of Scotland Get Current Business Accounts",
    "_postman_id": "e1a5366a-eef6-4a2e-94cf-01f7e5d05569",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple BCA products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Business",
      "item": [
        {
          "id": "d3085e11-2347-4688-a407-7a4f2e17db56",
          "name": "getCurentBusinessAccounts",
          "request": {
            "url": "http://api.bankofscotland.co.uk/open-banking/v2.1/business-current-accounts/",
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
              "id": "838697de-3c43-4c3e-8ad3-c89bf3f3f1d8"
            }
          ]
        }
      ]
    }
  ]
}