{
  "info": {
    "name": "Yapily Retrieves details of personal current accounts for an institution",
    "_postman_id": "fa1a3f2b-13e7-409c-ae64-8022d5fe4550",
    "description": "Retrieves details of personal current accounts for an institution.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Accounts",
      "item": [
        {
          "id": "1329d9ca-bc95-4773-ada7-c08464b7a421",
          "name": "getAccountsUsingGET",
          "request": {
            "url": "http://api.yapily.com:443/accounts",
            "method": "GET",
            "header": [
              {
                "key": "consent",
                "value": "{}",
                "description": "Consent Token",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get accounts."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c690df99-5028-4dd5-8daf-11f49b81aed8"
            }
          ]
        }
      ]
    },
    {
      "name": "Account",
      "item": [
        {
          "id": "d7207a0d-761a-4ca4-8aea-3fedb0f013ba",
          "name": "getAccountUsingGET",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.yapily.com",
              "path": [
                "accounts/:accountId"
              ],
              "port": "443",
              "variable": [
                {
                  "id": "accountId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "consent",
                "value": "{}",
                "description": "Consent Token",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "781fb9b8-6a0f-476c-867c-250fb335e6a7"
            }
          ]
        },
        {
          "id": "f9904bbe-8116-4c4d-9828-f5c1bdeab616",
          "name": "getTransactionsUsingGET",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.yapily.com",
              "path": [
                "accounts/:accountId/transactions"
              ],
              "port": "443",
              "variable": [
                {
                  "id": "accountId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "consent",
                "value": "{}",
                "description": "Consent Token",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get account transactions."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1a4ce942-aab1-4ccd-aa22-024ad1e18521"
            }
          ]
        }
      ]
    },
    {
      "name": "Identity",
      "item": [
        {
          "id": "aa43276d-a62f-45a5-b857-78acf8bf03fa",
          "name": "identityUsingGET",
          "request": {
            "url": "http://api.yapily.com:443/identity",
            "method": "GET",
            "header": [
              {
                "key": "consent",
                "value": "{}",
                "description": "Consent Token",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get identity."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4c4d8a3c-7bb6-4910-b9b7-ff4aeb153a1a"
            }
          ]
        }
      ]
    },
    {
      "name": "Retrieves",
      "item": [
        {
          "id": "95f4afee-e5ad-4877-a99a-7f4da243c56c",
          "name": "getInstitutionsUsingGET",
          "request": {
            "url": "http://api.yapily.com:443/institutions",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the list of institutions available in yapily."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d61b9438-cac5-4fe1-9402-39ebca22bf25"
            }
          ]
        },
        {
          "id": "8ca32bb2-fc55-420d-9d1a-9dd86c3f191c",
          "name": "getInstitutionUsingGET",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.yapily.com",
              "path": [
                "institutions/:institutionId"
              ],
              "port": "443",
              "variable": [
                {
                  "id": "institutionId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves details of a specific institution available in yapily."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7e491b00-4870-4aac-b31d-448505997a63"
            }
          ]
        },
        {
          "id": "77f7ce9c-3c95-4306-b757-d7ac67a2aec4",
          "name": "getPersonalCurrentAccountsUsingGET",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.yapily.com",
              "path": [
                "institutions/:institutionId/personal-current-accounts"
              ],
              "port": "443",
              "variable": [
                {
                  "id": "institutionId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves details of personal current accounts for an institution."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "786e6717-e0d5-4a9c-b3b7-716d02c67c45"
            }
          ]
        }
      ]
    }
  ]
}