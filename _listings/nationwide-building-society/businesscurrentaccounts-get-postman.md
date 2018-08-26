{
  "info": {
    "name": "Nationwide Building Society Get Current Business Accounts",
    "_postman_id": "dcac1345-e5fb-4f3f-8271-a52d4db01f5d",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple BCA products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Current",
      "item": [
        {
          "id": "b8fc3005-00bd-42e6-a376-e4f2b85c2af2",
          "name": "getCurentBusinessAccounts",
          "request": {
            "url": "http://openapi.nationwide.co.uk/open-banking/v2.1/business-current-accounts/",
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
              "id": "ca67cdcd-1488-4aa0-9d16-e39e5832109b"
            }
          ]
        }
      ]
    }
  ]
}