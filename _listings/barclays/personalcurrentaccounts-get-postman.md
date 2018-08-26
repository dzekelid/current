{
  "info": {
    "name": "Barclays Get Current Personal Accounts",
    "_postman_id": "ce35a509-46c9-4c58-b8c4-a83e1d7febc4",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple PCA products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Personal",
      "item": [
        {
          "id": "957c8471-7f84-4102-a407-2d2175441510",
          "name": "getCurrentPersonalAccounts",
          "request": {
            "url": "http://atlas.api.barclays/open-banking/v2.1/personal-current-accounts/",
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
              "id": "37924c6d-789c-46d0-92dc-f03f5263fe01"
            }
          ]
        }
      ]
    }
  ]
}