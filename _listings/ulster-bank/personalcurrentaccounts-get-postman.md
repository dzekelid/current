{
  "info": {
    "name": "Ulster Bank Get Current Personal Accounts",
    "_postman_id": "772af289-c721-4094-932a-74122b43f2cd",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple PCA products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Current",
      "item": [
        {
          "id": "c192cd59-84bf-464e-92f5-2323970a3728",
          "name": "getCurrentPersonalAccounts",
          "request": {
            "url": "http://openapi.ulsterbank.co.uk/open-banking/v2.1/personal-current-accounts/",
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
              "id": "a4b2fb5b-2bcf-4791-b711-fcb1d1519fa5"
            }
          ]
        }
      ]
    }
  ]
}