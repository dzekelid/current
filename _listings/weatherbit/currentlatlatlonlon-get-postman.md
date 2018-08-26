{
  "info": {
    "name": "Weatherbit Get Current Lat & Lon",
    "_postman_id": "292759e6-2de2-4f06-92d5-1878888ec211",
    "description": "Returns a Current Observation - given a lat, and a lon.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "weather",
      "item": [
        {
          "id": "7b18d663-0817-4437-b386-d44ff615c1e1",
          "name": "returns-a-current-observation--given-a-lat-and-a-lon",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.weatherbit.io",
              "path": [
                "v2.0",
                "current?lat=:lat&lon=:lon"
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
                  "id": "lat",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "lon",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a Current Observation - given a lat, and a lon"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9a706f0d-1809-42bf-a858-e16c344ed523"
            }
          ]
        }
      ]
    }
  ]
}