---
swagger: "2.0"
x-collection-name: Logicbroker
x-complete: 0
info:
  title: Logic Broker CommerceAPI Return the current status code of an invoice.
  version: 1.0.0
  description: Request rate limited to 10 requests per second with bursts up to 100
    requests.
host: stage.commerceapi.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/Invoices/{LogicbrokerKey}/Status:
    get:
      summary: Return the current status code of an invoice.
      description: Request rate limited to 10 requests per second with bursts up to
        100 requests.
      operationId: Invoice_GetInvoiceStatus
      x-api-path-slug: apiv1invoiceslogicbrokerkeystatus-get
      parameters:
      - in: path
        name: LogicbrokerKey
        description: The logicbroker key of the invoice to look up
      responses:
        200:
          description: OK
      tags:
      - Return
      - Current
      - Status
      - Code
      - Of
      - Invoice
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