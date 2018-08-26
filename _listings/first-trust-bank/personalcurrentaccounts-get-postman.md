{
  "info": {
    "name": "First Trust Bank (Open Banking) Get Current Personal Accounts",
    "_postman_id": "ee33afc9-191c-4732-8d01-ade21dbeac81",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple PCA products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Current",
      "item": [
        {
          "id": "4389d2e4-dd7a-4f29-9d58-1029ef2ba20c",
          "name": "getCurrentPersonalAccounts",
          "request": {
            "url": "http://openapi.firsttrustbank.co.uk/open-banking/v2.1/personal-current-accounts/",
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
              "id": "b073777d-2a17-4885-85ae-3a5feb609fd0"
            }
          ]
        }
      ]
    }
  ]
}