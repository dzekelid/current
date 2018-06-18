{
  "info": {
    "name": "Danske Bank Get Current Business Accounts",
    "_postman_id": "cb304ef5-20f2-48f0-9c28-7e642b9f1ea7",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple BCA products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "cee7c654-f8d8-4e5d-9bea-92c84fa346d1",
      "name": "getATMS",
      "request": {
        "url": "http://obp-data.danskebank.com/open-banking/v2.1/atms/",
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
          "id": "fb2dd7a3-9674-4239-aef3-a3f454a2c03d"
        }
      ]
    },
    {
      "id": "2c6d34be-92bd-4059-bcf9-09f9e209b001",
      "name": "getBranches",
      "request": {
        "url": "http://obp-data.danskebank.com/open-banking/v2.1/branches/",
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
          "id": "c8249397-37b6-4be5-bf36-b5e228e488d1"
        }
      ]
    },
    {
      "id": "bf952d56-9181-4f1b-9fe6-f0f7028c41e5",
      "name": "getCurrentPersonalAccounts",
      "request": {
        "url": "http://obp-data.danskebank.com/open-banking/v2.1/personal-current-accounts/",
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
          "id": "a45d6577-272e-4924-b470-66fe0d6a6aa2"
        }
      ]
    },
    {
      "id": "c9b234da-1f9a-44d3-a0b9-26c53ad6a318",
      "name": "getCurentBusinessAccounts",
      "request": {
        "url": "http://obp-data.danskebank.com/open-banking/v2.1/business-current-accounts/",
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
          "id": "d2ba23ef-3ce7-4a85-95ad-ad26b2796143"
        }
      ]
    }
  ]
}