{
  "info": {
    "name": "HSBC Get Current Business Accounts",
    "_postman_id": "3eeb916f-688d-46c3-b8d8-f6cd11026155",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple BCA products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Business",
      "item": [
        {
          "id": "43829198-c265-4b92-97c8-cbc48f55ce3e",
          "name": "getCurentBusinessAccounts",
          "request": {
            "url": "http://api.hsbc.com/open-banking/v2.1/business-current-accounts/",
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
              "id": "f9f96d7b-e8ff-4265-b31b-6d885722eb02"
            }
          ]
        }
      ]
    }
  ]
}