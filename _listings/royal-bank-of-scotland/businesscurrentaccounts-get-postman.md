{
  "info": {
    "name": "Royal Bank of Scotland Get Current Business Accounts",
    "_postman_id": "4e94c078-f4bf-48b4-84da-214947877fb8",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple BCA products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "0d2eeb03-1fa2-4642-a34d-130b202c7ee6",
      "name": "getATMS",
      "request": {
        "url": "http://openapi.rbs.co.uk/open-banking/v2.1/atms/",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can provide multiple ATMs."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "90857cc4-9de1-475c-8af4-8dd6dc273832"
        }
      ]
    },
    {
      "id": "0e417c03-f29c-4013-80c6-8cf4b7ad119b",
      "name": "getBranches",
      "request": {
        "url": "http://openapi.rbs.co.uk/open-banking/v2.1/branches/",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple branches."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "99d5df38-3454-4be4-b90a-060cf93ab31b"
        }
      ]
    },
    {
      "id": "910acfed-3ab4-4e2a-a86c-94e7a2274d2c",
      "name": "getCurrentPersonalAccounts",
      "request": {
        "url": "http://openapi.rbs.co.uk/open-banking/v2.1/personal-current-accounts/",
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
          "id": "910a5f58-f4ca-4799-8aef-92cd9c840b12"
        }
      ]
    },
    {
      "id": "b4d4f460-78b0-44c0-8457-0039b632aafd",
      "name": "getCurentBusinessAccounts",
      "request": {
        "url": "http://openapi.rbs.co.uk/open-banking/v2.1/business-current-accounts/",
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
          "id": "e38a4295-c4e2-47f2-90fa-df6224744672"
        }
      ]
    }
  ]
}