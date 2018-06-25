{
  "info": {
    "name": "Weatherbit Get Current IP",
    "_postman_id": "7c20d1cf-2e2d-48f3-b28b-0f490f2f561b",
    "description": "Returns a Current Observation - Given an IP address, or auto.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "weather",
      "item": [
        {
          "id": "19376d0f-96c9-4b76-a53b-7f70425faa26",
          "name": "returns-a-current-observation--given-an-ip-address-or-auto",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.weatherbit.io",
              "path": [
                "v2.0",
                "current?ip=:ip"
              ],
              "query": [
                {
                  "key": "callback",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "key",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "lang",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "marine",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "units",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "ip",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a Current Observation - Given an IP address, or auto"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "41607ab6-7f7f-4754-b413-673836c019e1"
            }
          ]
        }
      ]
    }
  ]
}