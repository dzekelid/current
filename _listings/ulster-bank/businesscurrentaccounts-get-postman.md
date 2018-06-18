{
  "info": {
    "name": "Ulster Bank Get Current Business Accounts",
    "_postman_id": "c09d8a1d-51b9-4e71-85ad-7af4cb9ddab2",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple BCA products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Current",
      "item": [
        {
          "id": "af482349-e612-4728-a8f0-820e998d0a43",
          "name": "getCurentBusinessAccounts",
          "request": {
            "url": "http://openapi.ulsterbank.co.uk/open-banking/v2.1/business-current-accounts/",
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
              "id": "1cb7d891-8fdf-4d32-8d31-0a1606d087a8"
            }
          ]
        }
      ]
    }
  ]
}