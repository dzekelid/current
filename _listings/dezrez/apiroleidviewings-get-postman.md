{
  "info": {
    "name": "Dezrez Get all of the viewings associated to the current property marketing role.",
    "_postman_id": "58f3bbcb-5201-4c3f-bfdb-26b1cf99a14e",
    "description": "Get all of the viewings associated to the current property marketing role..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "List",
      "item": [
        {
          "id": "8fef93ea-e13b-4c98-8c4e-a1b29a9fb308",
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
              "id": "1666acd3-d249-48d2-8397-1e9bf625f97b"
            }
          ]
        }
      ]
    },
    {
      "name": "Returns",
      "item": [
        {
          "id": "6b6d2f10-7e86-4b92-b75c-d724229fae85",
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
              "id": "8046f081-ef51-40a9-8b54-c43034484b35"
            }
          ]
        },
        {
          "id": "ebb01164-3e2d-4f86-be03-f9091cf262df",
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
              "id": "44704d48-0d91-4539-9570-cbc48bbb5778"
            }
          ]
        },
        {
          "id": "0152d8ef-a513-4ef8-9b69-f03beaf3171e",
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
              "id": "a2250123-8ed3-47ee-bc51-749d8f69995b"
            }
          ]
        },
        {
          "id": "d00c71c1-06a4-460d-b3d9-0580bb6b7e21",
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
              "id": "43529a44-419e-4b87-8034-9613c0ef3559"
            }
          ]
        },
        {
          "id": "6a201d59-444c-4048-8e4e-9c4a668a8e2c",
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
              "id": "154e33a5-a67b-43e0-b7da-5191b7d9486a"
            }
          ]
        },
        {
          "id": "5e4d381d-4461-4de8-aef5-22c45cc8a013",
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
              "id": "7452be09-a637-47a9-92b5-93f4c6514541"
            }
          ]
        },
        {
          "id": "0529de9b-eeb9-498b-8590-f09d65c2eec7",
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
              "id": "765f20a4-dd05-4abc-a1aa-cf6333b458ec"
            }
          ]
        },
        {
          "id": "48a3b4d1-a264-4efd-b8fe-046e495dafcd",
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
              "id": "f617632b-ce56-4664-8504-11ad77009d17"
            }
          ]
        },
        {
          "id": "cfebfe96-ab08-4bc0-b6c5-11653bc6e1d0",
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
              "id": "312c9c01-b72d-43e6-9d63-921ca8638329"
            }
          ]
        },
        {
          "id": "839a895d-7dd8-4939-8745-16f766566db7",
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
              "id": "364c7f75-0385-4b9f-a4d5-a92028a813cd"
            }
          ]
        },
        {
          "id": "f5de7919-bf8c-438d-9a35-c1ea4094e6e8",
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
              "id": "21569609-2068-417e-aa08-fe8e05d78edd"
            }
          ]
        },
        {
          "id": "704d5c97-0076-4751-bf28-59b919c37cf0",
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
              "id": "aa38a488-3ac9-4f5f-8195-592e67b50a3a"
            }
          ]
        }
      ]
    },
    {
      "name": "Live",
      "item": [
        {
          "id": "3614f141-5f3b-4049-a250-add8dc84688b",
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
              "id": "a94138d1-cb12-4350-aa16-5186880cbd07"
            }
          ]
        }
      ]
    },
    {
      "name": "Of",
      "item": [
        {
          "id": "8ae71961-c407-460f-aa5e-bf88e4174dab",
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
              "id": "119fb991-d59e-4b80-a363-c655ef40eec8"
            }
          ]
        },
        {
          "id": "e1eb464e-d855-4725-acba-e4225760cff1",
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
              "id": "8ff41a41-6c06-4b1f-9bff-a16ae5305490"
            }
          ]
        },
        {
          "id": "a4d399cd-10a7-42ef-af6e-c3ec04141cfc",
          "name": "Role_ViewingsByidBypageSizeBypageNumberByexcludeDrafts",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.dezrez.com",
              "path": [
                "api/role/:id/viewings"
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
            "description": "Get all of the viewings associated to the current property marketing role.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2d01f657-4d36-41e1-b9e0-2e145967f9aa"
            }
          ]
        }
      ]
    },
    {
      "name": "Basic",
      "item": [
        {
          "id": "ad6e9594-9f63-4017-9fe1-81a78dfe26d0",
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
              "id": "669b0fa6-9b6c-48f4-9334-5ff156842055"
            }
          ]
        }
      ]
    }
  ]
}