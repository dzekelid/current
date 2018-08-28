---
swagger: "2.0"
x-collection-name: EU VAT API
x-complete: 0
info:
  title: EU VAT API Retrieve all current EU VAT rates
  description: Retrieve all current eu vat rates.
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
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---