---
swagger: "2.0"
x-collection-name: Baltimore Open311
x-complete: 0
info:
  title: Baltimore Open311 Current Status
  description: Query the current status of an individual request
  termsOfService: (depends on server instance for example NYC http://dev.cityofchicago.org/docs/api/tos)
  contact:
    name: Open311 community
    url: http://wiki.open311.org/GeoReport_v2/
    email: discuss@lists.open311.org
  version: 1.0.0
host: 311.baltimorecity.gov
basePath: /open311/v2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /request/{service_request_id}.{response_format}:
    get:
      summary: Current Status
      description: Query the current status of an individual request
      operationId: query-the-current-status-of-an-individual-request
      x-api-path-slug: requestservice-request-id-response-format-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: service_request_id
        description: Is specified in the main URL path rather than an added query
          string parameter
      responses:
        200:
          description: OK
      tags:
      - "311"
      - Current
      - Status
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