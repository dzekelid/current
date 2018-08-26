{
  "info": {
    "name": "Bank of Scotland Get Current Personal Accounts",
    "_postman_id": "3898023c-d758-44f0-b802-0f939377ee46",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple PCA products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Personal",
      "item": [
        {
          "id": "574b2366-9f02-42c6-a310-2f00ac583bed",
          "name": "getCurrentPersonalAccounts",
          "request": {
            "url": "http://api.bankofscotland.co.uk/open-banking/v2.1/personal-current-accounts/",
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
              "id": "53193d9e-ec78-48a2-b5c1-520f9bb1903d"
            }
          ]
        }
      ]
    }
  ]
}