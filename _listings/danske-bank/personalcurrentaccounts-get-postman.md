{
  "info": {
    "name": "Danske Bank Get Current Personal Accounts",
    "_postman_id": "4a4dd493-da41-4493-8d62-6d9901978413",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple PCA products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "dc140855-4cb2-420a-8da1-1b3516a45755",
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
          "id": "f0bcd83b-b2b3-4996-9ef2-71969b819db0"
        }
      ]
    },
    {
      "id": "39056f2e-686d-428a-95d7-969e3633787b",
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
          "id": "f7d726fc-8ea0-436c-9992-35a254560d9f"
        }
      ]
    },
    {
      "id": "f409908e-0fcc-4ded-8e50-6bc2c61f51c6",
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
          "id": "26eeafe8-ec1f-496d-8ada-4880d192954d"
        }
      ]
    }
  ]
}