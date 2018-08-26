---
swagger: "2.0"
x-collection-name: EU VAT API
x-complete: 1
info:
  title: VAT API
  description: a-developer-friendly-api-to-help-your-business-achieve-vat-compliance
  version: "1"
host: vatapi.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /usage-check:
    get:
      summary: Check api requests remaining on current subscription plan
      description: Check api requests remaining on current subscription plan.
      operationId: api_usage
      x-api-path-slug: usagecheck-get
      parameters:
      - in: header
        name: Response-Type
        description: The default response type is application/json if you would like
          to receive an XML response then set this to XML
      responses:
        200:
          description: OK
      tags:
      - Check
      - Api
      - Requests
      - Remaining
      - "On"
      - Current
      - Subscription
      - Plan
  /vat-rates:
    get:
      summary: Retrieve all current EU VAT rates
      description: Retrieve all current eu vat rates.
      operationId: vat_rates
      x-api-path-slug: vatrates-get
      parameters:
      - in: header
        name: Response-Type
        description: The default response type is application/json if you would like
          to receive an XML response then set this to XML
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - ""
      - Current
      - EU
      - VAT
      - Rates
---