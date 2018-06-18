{
  "info": {
    "name": "Lloyds Bank Get Current Personal Accounts",
    "_postman_id": "ec8ab069-8b38-44f6-906e-7a8e74c631c5",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple PCA products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Personal",
      "item": [
        {
          "id": "e3dea801-0de6-4195-98f5-d96382d3fba3",
          "name": "getCurrentPersonalAccounts",
          "request": {
            "url": "http://api.lloydsbank.com/open-banking/v2.1/personal-current-accounts/",
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
              "id": "b7ca34b3-0a49-4d86-afb3-7c5e5a005c68"
            }
          ]
        }
      ]
    }
  ]
}