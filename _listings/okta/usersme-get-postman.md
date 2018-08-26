{
  "info": {
    "name": "Okta Get Current User",
    "_postman_id": "35944407-4a7c-48dc-875a-00bc52f32f46",
    "description": "Get current user.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Current",
      "item": [
        {
          "id": "f17c9a3e-37c9-458e-a585-f7678e4b236a",
          "name": "getUsersMe",
          "request": {
            "url": "http://example.com/api/v1/users/me",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get current user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "96528061-6d0d-4644-91dc-346bdf1a53f7"
            }
          ]
        }
      ]
    }
  ]
}