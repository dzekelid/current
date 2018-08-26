{
  "info": {
    "name": "Dezrez Get all of the offers associated to the current property marketing role.",
    "_postman_id": "0684e890-bf41-4c9d-8883-9b1f9ca1becb",
    "description": "Get all of the offers associated to the current property marketing role..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "List",
      "item": [
        {
          "id": "5cb8908a-688b-4132-9d5e-18043bc2f9b2",
          "name": "AccountingSystem_GetOfficeAccounts",
          "request": {
            "url": "http://api.dezrez.com/api/accountingsystem/officeaccounts",
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
            "description": "Get list of office accounts associated with the accounting system."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2e324135-0a40-4460-ab5a-dfa965aa0a88"
            }
          ]
        }
      ]
    },
    {
      "name": "Returns",
      "item": [
        {
          "id": "384e30bc-ee70-4215-982e-8e6f84909f9d",
          "name": "DocumentGeneration_GetLetterTemplateByletterTemplateId",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.dezrez.com",
              "path": [
                "api/documentgeneration/lettertemplate/:letterTemplateId"
              ],
              "variable": [
                {
                  "id": "letterTemplateId",
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
            "description": "Returns a list of lettertemplates associated to this agency."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b5c2133e-2fe7-4f15-82f8-7f48fcdd0b70"
            }
          ]
        },
        {
          "id": "7663ee07-70ed-422a-93aa-3e5f8e13dff2",
          "name": "DocumentGeneration_GetPrintableMergeTemplates",
          "request": {
            "url": "http://api.dezrez.com/api/documentgeneration/mergetemplates",
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
            "description": "Returns a list of lettertemplates associated to this agency."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "de228780-d194-49bf-8f59-a199d665c0fc"
            }
          ]
        },
        {
          "id": "73228f12-2ef5-4372-99cb-c6b1e9d7eb5d",
          "name": "DocumentGeneration_GetUnusedMergeTemplates",
          "request": {
            "url": "http://api.dezrez.com/api/documentgeneration/unusedmergetemplates",
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
            "description": "Returns a list of lettertemplates associated to this agency that are not currently used in any envelope templates."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1f0a73f0-7689-43a9-825c-7f7343bfa655"
            }
          ]
        },
        {
          "id": "c713fd6d-ed62-4dbb-b4ea-2f98e786fc39",
          "name": "DocumentGeneration_GetTemplatesUsingAnalyticsByanalyticsId",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.dezrez.com",
              "path": [
                "api/documentgeneration/templatesusinganalytics/:analyticsId"
              ],
              "variable": [
                {
                  "id": "analyticsId",
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
            "description": "Returns a list of lettertemplates associated to this agency and to a particular google analyitics campaign."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "06a43710-4df9-4798-8389-b03cf9e410b5"
            }
          ]
        },
        {
          "id": "9a3793e0-8177-4fa1-bcfa-7c97a23b70c4",
          "name": "DocumentGeneration_GetPrintableInsertableTemplates",
          "request": {
            "url": "http://api.dezrez.com/api/documentgeneration/insertabletemplates",
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
            "description": "Returns a list of insertable templates associated to this agency."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "887c3c59-122d-4556-9a43-7ca023b151bb"
            }
          ]
        },
        {
          "id": "6c2028f5-4155-4a27-984c-462d5b54ff98",
          "name": "DocumentGeneration_GetPrintableHeaderTemplates",
          "request": {
            "url": "http://api.dezrez.com/api/documentgeneration/headertemplates",
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
            "description": "Returns a list of header templates associated to this agency with their associated brand info."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b13d1f68-429f-46a9-9d16-83e16509f004"
            }
          ]
        },
        {
          "id": "5e814949-896e-4b44-b5cf-36da228397ec",
          "name": "DocumentGeneration_GetEnvelopeTemplates",
          "request": {
            "url": "http://api.dezrez.com/api/documentgeneration/envelopetemplates",
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
            "description": "Returns a list of envelope templates associated to this agency."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "15ec63c8-0ead-4f76-96b2-353fc84d3e7e"
            }
          ]
        },
        {
          "id": "1a843f79-2600-4ab1-90ee-e7e43e3dfac4",
          "name": "DocumentGeneration_GetEnvelopeTemplatePacks",
          "request": {
            "url": "http://api.dezrez.com/api/documentgeneration/envelopetemplatepacks",
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
            "description": "Returns a list of envelope template packs associated to this agency."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1ea9413d-b53c-408a-b8c1-bf55043de9b9"
            }
          ]
        },
        {
          "id": "50147d75-1754-4ab2-a290-680607e50520",
          "name": "DocumentGeneration_GetEnvelopeTemplatePackTypesByinUseOnly",
          "request": {
            "url": "http://api.dezrez.com/api/documentgeneration/envelopetemplatepacktypes?inUseOnly=%7B%7D",
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
            "description": "Returns a list of envelope template packs associated to this agency."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "62b11e91-d817-48ba-86a4-e08f09189d8d"
            }
          ]
        },
        {
          "id": "6b48e72d-adf6-4a90-8c5d-fad466e2610b",
          "name": "DocumentGeneration_GetEmailTemplates",
          "request": {
            "url": "http://api.dezrez.com/api/documentgeneration/emailtemplates",
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
            "description": "Returns a list of email templates associated to this agency."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cbef0bfe-e46c-4108-8dac-83756ba504aa"
            }
          ]
        },
        {
          "id": "ee5d87ff-bad4-409e-aca0-53b418feb29f",
          "name": "DocumentGeneration_GetTemplatesBytemplateType",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.dezrez.com",
              "path": [
                "api/documentgeneration/templates/:templateType"
              ],
              "variable": [
                {
                  "id": "templateType",
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
            "description": "Returns a list of mergable templates for any type associated to this agency."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fd76ab37-aee3-43fa-a8e2-4e0f718ab508"
            }
          ]
        },
        {
          "id": "65411d6a-4803-4662-a491-ad5181128382",
          "name": "DocumentGeneration_GetSmsTemplates",
          "request": {
            "url": "http://api.dezrez.com/api/documentgeneration/smstemplates",
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
            "description": "Returns a list of sms templates associated to this agency."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e2f11d9d-25f0-45d3-b3e6-5c1324db4378"
            }
          ]
        }
      ]
    },
    {
      "name": "Live",
      "item": [
        {
          "id": "b0fa2dc3-7954-4762-9d26-c029caec268a",
          "name": "Portal_GetLivePortalInformationRecordsForRoleByroleId",
          "request": {
            "url": "http://api.dezrez.com/api/admin/portal/getportaluploadsforrole?roleId=%7B%7D",
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
            "description": "Get all the live portal uploads associated with a property marketing role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "33fb3644-c61f-4f2c-8b9c-c5cf3704af3a"
            }
          ]
        }
      ]
    },
    {
      "name": "Of",
      "item": [
        {
          "id": "440ed325-95c1-4708-958a-b21c73c37578",
          "name": "Property_ValuationsByidBypageSizeBypageNumber",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.dezrez.com",
              "path": [
                "api/property/:id/valuations"
              ],
              "query": [
                {
                  "key": "pageNumber",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "pageSize",
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
            "description": "Get all of the valuations associated to the current owner of the property.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f024be3d-4be1-4bcf-ab10-375d8cc2086a"
            }
          ]
        },
        {
          "id": "19c9e4b7-baf1-4063-bd26-216ba341938a",
          "name": "Role_OffersByidBypageSizeBypageNumberByexcludeDrafts",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.dezrez.com",
              "path": [
                "api/role/:id/offers"
              ],
              "query": [
                {
                  "key": "excludeDrafts",
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
            "description": "Get all of the offers associated to the current property marketing role.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "00c2d426-8b65-445c-99b3-c61653eb50e6"
            }
          ]
        }
      ]
    }
  ]
}