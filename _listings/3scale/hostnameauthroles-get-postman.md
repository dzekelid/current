{
  "info": {
    "name": "3scale Current Roles",
    "_postman_id": "1048637f-f610-48ed-9fa7-32aab8225f78",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "8027e555-2747-4c7d-b729-edc6a8c6c215",
      "name": "UnnammedEndpointGet",
      "request": {
        "url": "http://http://",
        "method": "GET",
        "header": [
          {
            "key": "x-client-auth",
            "value": "{}",
            "description": "",
            "disabled": false
          },
          {
            "key": "x-client-bearer-token",
            "value": "{}",
            "description": "",
            "disabled": false
          },
          {
            "key": "Accept",
            "value": "*/*",
            "disabled": false
          }
        ],
        "body": {
          "mode": "raw"
        },
        "description": "Once a user has authorized a client to communicate on their behalf (via the `auth/authorize` endpoint), the client can use the generated token in their `x-client-bearer-token` header to retreive the user's information from this endpoint."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "548b4243-40dd-4ce6-8a71-cd7b7370d254"
        }
      ]
    },
    {
      "id": "5347cff8-a93a-4828-8f66-f097d6c3c9d2",
      "name": "AuthRolesByHostnameGet",
      "request": {
        "url": {
          "protocol": "http",
          "host": "http",
          "path": [
            ":hostname/auth/roles"
          ],
          "variable": [
            {
              "id": "hostname",
              "value": "{}",
              "type": "string"
            }
          ]
        },
        "method": "GET",
        "header": [
          {
            "key": "x-client-auth",
            "value": "{}",
            "description": "",
            "disabled": false
          },
          {
            "key": "x-client-bearer-token",
            "value": "{}",
            "description": "",
            "disabled": false
          },
          {
            "key": "Accept",
            "value": "*/*",
            "disabled": false
          }
        ],
        "body": {
          "mode": "raw"
        },
        "description": "Current Roles"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "a33b9b26-92eb-46af-8d6e-730474040e28"
        }
      ]
    }
  ]
}