{
  "info": {
    "name": "Dezrez Get a basic list of offers associated to the current property marketing role.",
    "_postman_id": "b779f623-c36d-44ab-8348-16c3a7c694e4",
    "description": "Get a basic list of offers associated to the current property marketing role..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "List",
      "item": [
        {
          "id": "c6e5443e-085c-4b6a-bec6-878ea0dc4227",
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
              "id": "87dc7ea8-3c2a-440b-b152-64016fcbdbe6"
            }
          ]
        }
      ]
    },
    {
      "name": "Returns",
      "item": [
        {
          "id": "f81b012b-a956-401a-9acf-d23191542870",
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
              "id": "91f5a8e0-599f-4505-b516-1fc75a333cd4"
            }
          ]
        },
        {
          "id": "2a6d13e4-86bb-4c6f-b46f-c12ac2f3bfcd",
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
              "id": "b6ad0dff-57fe-4623-a379-328e82770b32"
            }
          ]
        },
        {
          "id": "6737e116-27b3-4ec4-afdf-d608d7d6da53",
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
              "id": "66144237-cba1-4a88-a0c9-8e1226a2db97"
            }
          ]
        },
        {
          "id": "7c04f52e-632d-435d-8c0d-762b4a6c5a5c",
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
              "id": "14609824-6c97-4dcc-863a-87b1b3b521e1"
            }
          ]
        },
        {
          "id": "0acce811-d856-44e3-8169-8b333376153f",
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
              "id": "6496d258-4901-480c-97ed-4391a96892be"
            }
          ]
        },
        {
          "id": "7a70af58-e369-4572-8db9-624908dfc86d",
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
              "id": "d87375f5-360d-4a90-9d0e-c8fca17a5573"
            }
          ]
        },
        {
          "id": "aa0ffe5b-cda4-4cd4-adf9-883d3909028d",
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
              "id": "6f24d10b-f99f-40ea-b527-b5a3ff20cf46"
            }
          ]
        },
        {
          "id": "ee0cdc29-eeb7-4c50-96a8-15e2bce8afda",
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
              "id": "18b606c1-536f-459c-8e19-5ad460fb7aee"
            }
          ]
        },
        {
          "id": "5e2882c2-96e9-4d54-992b-31aae284c896",
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
              "id": "9a08f2ec-f711-47bc-a4dc-484010f73ccb"
            }
          ]
        },
        {
          "id": "9404540b-a627-4d37-b65e-c8b39d0b5df8",
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
              "id": "1b98cc51-0268-4cff-a6ab-cacc90f865c6"
            }
          ]
        },
        {
          "id": "a1673899-6ea1-457d-9d63-24e93cdaad7f",
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
              "id": "ec138cf5-c7e2-42e2-991a-f794374f86bf"
            }
          ]
        },
        {
          "id": "3d8e7683-915d-46da-8b4e-51fbf7d984ff",
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
              "id": "7e896017-2fd4-4f25-81f0-a605e01a014c"
            }
          ]
        }
      ]
    },
    {
      "name": "Live",
      "item": [
        {
          "id": "ca4a22b9-8a7d-47ed-99d5-ad5a7299a370",
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
              "id": "ab7a8224-1fa8-4bfc-a8e8-6997d9713af9"
            }
          ]
        }
      ]
    },
    {
      "name": "Of",
      "item": [
        {
          "id": "2ebbda9f-63a4-4973-911b-ce8abbfb57b2",
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
              "id": "93ebe9c7-66ab-4abc-9d38-6574dad91d0d"
            }
          ]
        },
        {
          "id": "6e4493c2-5ecc-4260-bda5-0b1488a99497",
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
              "id": "7a8738dc-ac2c-4f21-9c13-a90aa0d2182d"
            }
          ]
        }
      ]
    },
    {
      "name": "Basic",
      "item": [
        {
          "id": "72ce4348-33d4-45fc-93d7-5403f7e8a374",
          "name": "Role_OffersBasicByid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.dezrez.com",
              "path": [
                "api/role/:id/offersbasic"
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
            "description": "Get a basic list of offers associated to the current property marketing role.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "abdc8648-d6f5-4fae-b38c-b1236ce3ff06"
            }
          ]
        }
      ]
    }
  ]
}