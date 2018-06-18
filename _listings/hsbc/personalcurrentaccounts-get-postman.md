{
  "info": {
    "name": "HSBC Get Current Personal Accounts",
    "_postman_id": "d1cf613a-a314-44ac-b778-452136081549",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple PCA products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Personal",
      "item": [
        {
          "id": "d5e18231-17bc-481b-8cfc-785c83d78082",
          "name": "getCurrentPersonalAccounts",
          "request": {
            "url": "http://api.hsbc.com/open-banking/v2.1/personal-current-accounts/",
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
              "id": "db157e89-3efa-4ee8-886a-ad64c9eebfca"
            }
          ]
        }
      ]
    }
  ]
}