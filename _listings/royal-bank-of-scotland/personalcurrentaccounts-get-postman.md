{
  "info": {
    "name": "Royal Bank of Scotland Get Current Personal Accounts",
    "_postman_id": "32af40aa-75f0-4800-b24d-cd66cd3fb96e",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple PCA products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "4f27b58c-6316-4372-b3cc-2ff5ccb24e5f",
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
          "id": "e92cdcb5-4220-4ca4-9023-697c92059b2d"
        }
      ]
    },
    {
      "id": "7e8e1cbf-be72-4355-a489-f0ad460b333a",
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
          "id": "50850a48-e225-4a46-9ea8-1c14fc9dea8f"
        }
      ]
    },
    {
      "id": "fc223ba7-36ce-44c2-9feb-821e4e662048",
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
          "id": "64ae506e-d20c-4898-bbf5-75718b19c669"
        }
      ]
    }
  ]
}