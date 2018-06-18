{
  "info": {
    "name": "NatWest Get Current Personal Accounts",
    "_postman_id": "4ac90adc-4c54-4275-9943-46400539e207",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple PCA products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "62627524-7f9e-4a8a-9c94-cdf6c6e3c1cc",
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
          "id": "6c0cffee-97c4-4a36-b3fc-dd0d1f9ce87e"
        }
      ]
    },
    {
      "id": "5d453351-3d11-4506-b803-323fdbd5a345",
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
          "id": "15fb3f43-6016-4adf-9205-6066e53732bf"
        }
      ]
    },
    {
      "id": "cde23802-9b7b-4cff-9cb7-ef3e49039a28",
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
          "id": "da74fb30-a069-4e44-b7c8-63b07da56626"
        }
      ]
    }
  ]
}