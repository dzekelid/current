{
  "info": {
    "name": "3scale Current User",
    "_postman_id": "ca0fd58b-2aec-4928-a124-157194b880b9",
    "description": "Once a user has authorized a client to communicate on their behalf (via the `auth/authorize` endpoint), the client can use the generated token in their `x-client-bearer-token` header to retreive the user's information from this endpoint.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "a0142120-d93f-4a75-a6ee-60c43f554848",
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
          "id": "1734f08e-0909-431f-b59b-861576a6e399"
        }
      ]
    }
  ]
}