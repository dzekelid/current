{
  "info": {
    "name": "Current Status API Current Status of Monitor",
    "_postman_id": "e1a002b7-f3cd-46d9-b78a-44526c363d3c",
    "description": "Request Example",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Current Status",
      "item": [
        {
          "id": "fc622784-ee8e-48c6-9003-bed73a3c6f2d",
          "name": "current-status-of-monitor",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.site24x7.com.",
              "path": [
                "current_status/:monitor_id"
              ],
              "variable": [
                {
                  "id": "monitor_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Request Example"
          },
          "response": [
            {
              "code": 200,
              "name": "Response_200",
              "id": "04b01e78-fe85-4b6e-89de-5927865138c1"
            },
            {
              "status": "100 KiB",
              "code": 500,
              "name": "Response_500",
              "id": "68c945ca-6d0f-4bed-8e37-b91a314ba13a"
            }
          ]
        }
      ]
    }
  ]
}