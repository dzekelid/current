{
  "info": {
    "name": "Barclays Get Current Business Accounts",
    "_postman_id": "a02e9d2f-7a2a-493f-abc1-195baa6acd4c",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple BCA products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Business",
      "item": [
        {
          "id": "337f1126-284b-4f5e-90ff-a3766ee833c6",
          "name": "getCurentBusinessAccounts",
          "request": {
            "url": "http://atlas.api.barclays/open-banking/v2.1/business-current-accounts/",
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
              "id": "862d9987-619a-46d3-b798-53e78210617a"
            }
          ]
        }
      ]
    }
  ]
}