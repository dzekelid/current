{
  "info": {
    "name": "Azure Blockchain Workbench Delete Applications",
    "_postman_id": "5f032807-f356-4a5e-a8d4-3730a1fa1b89",
    "description": "Deletes the specified blockchain application. This method can only be performed by users who are\n             Workbench administrators. NOTE: Currently not implemented.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Applications",
      "item": [
        {
          "id": "7da6ae4e-701d-45e6-aad3-dfee23330a50",
          "name": "ApplicationsGet",
          "request": {
            "url": "{{default}}/api/v1/applications?enabled=%7B%7D&skip=%7B%7D&sortBy=%7B%7D&top=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Lists all blockchain applications to which a user has access in Workbench. Users who are Workbench administrators get\n             all blockchain applications. Non-Workbench administrators get all blockchain applications for which they have at least one\n             associated application role or an associated smart contract instance role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "63aad605-5d4d-4f49-9f72-c8c6b2504e7d"
            }
          ]
        },
        {
          "id": "81ccf056-51ab-4b80-9ae8-c0833a9f9e14",
          "name": "ApplicationsPost",
          "request": {
            "url": "{{default}}/api/v1/applications",
            "method": "POST",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "appFile",
                  "value": "{}",
                  "disabled": false,
                  "description": "Upload Application File"
                }
              ]
            },
            "description": "Creates a new blockchain application. This method can only be performed by users who are\n             Workbench administrators."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "48fab008-5a3e-4e0b-993c-b7d1f0db0f01"
            }
          ]
        },
        {
          "id": "963297bb-8f3b-4127-94c4-44a336faf58b",
          "name": "ApplicationGet",
          "request": {
            "url": {
              "host": "{{default}}",
              "path": [
                "api/v1/applications/:applicationId"
              ],
              "variable": [
                {
                  "id": "applicationId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets the blockchain application matching a specific application ID. Users who are Workbench administrators get\n             the blockchain application. Non-Workbench administrators get the blockchain application if they have at least one associated\n             application role or is associated with a smart contract instance role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "25246275-2693-4ee4-a20e-c2159cf11b19"
            }
          ]
        },
        {
          "id": "8e10b028-4dd6-4ff4-aa66-1f91528d62b6",
          "name": "ApplicationDelete",
          "request": {
            "url": {
              "host": "{{default}}",
              "path": [
                "api/v1/applications/:applicationId"
              ],
              "variable": [
                {
                  "id": "applicationId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified blockchain application. This method can only be performed by users who are\n             Workbench administrators. NOTE: Currently not implemented."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d2c78fad-c9f1-4b1b-ad58-1e74800e2b32"
            }
          ]
        }
      ]
    }
  ],
  "variable": [
    {
      "key": "default",
      "value": "http://www.example.com/"
    }
  ]
}