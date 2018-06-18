{
  "info": {
    "name": "NatWest Get Current Business Accounts",
    "_postman_id": "5ce7530d-2960-41a3-8675-5bbffcb2b4da",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple BCA products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "509a7106-9549-4250-8ff9-c785ebda991d",
      "name": "getATMS",
      "request": {
        "url": "http://openapi.natwest.com/open-banking/v2.1/atms/",
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
          "id": "25695e36-7602-44ca-8ee9-5115aec09eed"
        }
      ]
    },
    {
      "id": "bf499ee0-1ac1-48e2-88c3-1c9f0212ad8e",
      "name": "getBranches",
      "request": {
        "url": "http://openapi.natwest.com/open-banking/v2.1/branches/",
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
          "id": "02eea0f6-4f2a-4f8e-97f2-9bdf3f3000e5"
        }
      ]
    },
    {
      "id": "35275590-390a-4837-bc3b-31aed8412061",
      "name": "getCurrentPersonalAccounts",
      "request": {
        "url": "http://openapi.natwest.com/open-banking/v2.1/personal-current-accounts/",
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
          "id": "9ec431cb-4bcb-4259-89e8-b592ddb7ac9c"
        }
      ]
    },
    {
      "id": "f4bd567f-09c7-4d8b-94a6-20d7cb26b56a",
      "name": "getCurentBusinessAccounts",
      "request": {
        "url": "http://openapi.natwest.com/open-banking/v2.1/business-current-accounts/",
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
          "id": "e9d8be0f-0ae6-4d2e-81d2-d8e739c75125"
        }
      ]
    }
  ]
}