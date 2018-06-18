---
swagger: "2.0"
x-collection-name: Bank of Ireland
x-complete: 1
info:
  title: Bank of Ireland
  description: this-is-an-openapi-definition-for-the-standard-set-of-open-banking-httpopenbankingapis-io-apis-for-the-bank-of-ireland-
  termsOfService: https://www.openbanking.org.uk/open-licence/
  contact:
    name: API Evangelist
    url: https://apievangelist.com
    email: info@apievangelist.com
  version: 1.0.0
host: openapi.bankofireland.com
basePath: open-banking/v2.1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  personal-current-accounts/:
    get:
      summary: Get Personal Current Accounts
      description: This endpoint can contain multiple brands owned by a particular
        banking group. Each brand can own multiple PCA products.
      operationId: getCurrentPersonalAccounts
      x-api-path-slug: personalcurrentaccounts-get
      responses:
        200:
          description: OK
      tags:
      - Personal
      - Current
      - Accounts
  business-current-accounts/:
    get:
      summary: Get Business Current Accounts
      description: This endpoint can contain multiple brands owned by a particular
        banking group. Each brand can own multiple BCA products.
      operationId: getCurentBusinessAccounts
      x-api-path-slug: businesscurrentaccounts-get
      responses:
        200:
          description: OK
      tags:
      - Business
      - Current
      - Accounts
---