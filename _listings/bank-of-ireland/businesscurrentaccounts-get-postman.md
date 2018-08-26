{
  "info": {
    "name": "Bank of Ireland Get Business Current Accounts",
    "_postman_id": "51a9fde5-b32c-4ba8-9219-c24361127386",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple BCA products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Business",
      "item": [
        {
          "id": "bd30919a-1865-4fd1-a47a-721fef209e7c",
          "name": "getCurentBusinessAccounts",
          "request": {
            "url": "http://openapi.bankofireland.com/open-banking/v2.1/business-current-accounts/",
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
              "id": "dc29aa80-fc10-4f1c-aa5f-8cf8d608eb72"
            }
          ]
        }
      ]
    }
  ]
}