{
  "info": {
    "name": "Nationwide Building Society Get Current Personal Accounts",
    "_postman_id": "31b3ebe0-926a-4c3d-a5d9-5185f3693205",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple PCA products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Current",
      "item": [
        {
          "id": "0ccf22c6-e8be-4768-904b-96bc6f8d489c",
          "name": "getCurrentPersonalAccounts",
          "request": {
            "url": "http://openapi.nationwide.co.uk/open-banking/v2.1/personal-current-accounts/",
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
              "id": "3bf563c6-0d11-47f2-abf1-c111c755140a"
            }
          ]
        }
      ]
    }
  ]
}