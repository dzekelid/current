{
  "info": {
    "name": "Dezrez Get property events for the current owner by its Id",
    "_postman_id": "677bd003-42e5-4386-aaff-f9e25e67221e",
    "description": "Get property events for the current owner by its id.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "S",
      "item": [
        {
          "id": "cdd5006c-6a47-4b21-8bdb-9c25ccccaf85",
          "name": "Agency_GetVatRateByvatRateTypeByvatDate",
          "request": {
            "url": "http://api.dezrez.com/api/agency/getvatrate?vatDate=%7B%7D&vatRateType=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Rezi-Api-Version",
                "value": "{}",
                "description": "Specifies which version of the API to call",
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
            "description": "Gets the current vat rate unless the date is specified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c7b37f1f-4765-41d9-9aa3-548e245ea355"
            }
          ]
        }
      ]
    },
    {
      "name": "Details",
      "item": [
        {
          "id": "9ebd632a-d213-4dc0-a4b5-68e10b5c5550",
          "name": "Agency_Get",
          "request": {
            "url": "http://api.dezrez.com/api/Agency",
            "method": "GET",
            "header": [
              {
                "key": "Rezi-Api-Version",
                "value": "{}",
                "description": "Specifies which version of the API to call",
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
            "description": "Get details of the current users agency."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0dfc040b-2e71-4000-aba4-888e44f989a9"
            }
          ]
        }
      ]
    },
    {
      "name": "Sends",
      "item": [
        {
          "id": "6d4acecf-c727-4584-9f5c-bf78c4cbe89a",
          "name": "CorePlatformState_SendPendingAlerts",
          "request": {
            "url": "http://api.dezrez.com/api/coreplatformstate/sendpendingalerts",
            "method": "POST",
            "header": [
              {
                "key": "Rezi-Api-Version",
                "value": "{}",
                "description": "Specifies which version of the API to call",
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
            "description": "Sends alerts for all current platform issues.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "59107b31-3411-4349-9853-62bb89db0c49"
            }
          ]
        }
      ]
    },
    {
      "name": "Property",
      "item": [
        {
          "id": "c44b2095-2568-4c56-9f7d-f34196d21138",
          "name": "Property_OwnersEventsByidBypageSizeBypageNumberBybranchIdByfromBytoBytypeByeventCategoryType",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.dezrez.com",
              "path": [
                "api/property/:id/owners/events"
              ],
              "query": [
                {
                  "key": "branchId",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "eventCategoryType",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "from",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "pageNumber",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "pageSize",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "to",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "type",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Rezi-Api-Version",
                "value": "{}",
                "description": "Specifies which version of the API to call",
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
            "description": "Get property events for the current owner by its id."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "da601266-4df6-4a99-930f-b41fe7e586d3"
            }
          ]
        }
      ]
    }
  ]
}