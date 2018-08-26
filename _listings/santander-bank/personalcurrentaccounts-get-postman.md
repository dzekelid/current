{
  "info": {
    "name": "Santander Bank Get Current Personal Accounts",
    "_postman_id": "433e694b-f4aa-4d99-8bbe-fed5e6dc2c9a",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple PCA products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Current",
      "item": [
        {
          "id": "c464e835-6a0b-4f11-acec-788dd723a13e",
          "name": "getCurrentPersonalAccounts",
          "request": {
            "url": "http://openapi.santander.co.uk/open-banking/v2.1/personal-current-accounts/",
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
              "id": "9d032c17-c8b4-47b5-94d7-20f902ae782f"
            }
          ]
        }
      ]
    }
  ]
}