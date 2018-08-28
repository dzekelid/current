swagger: "2.0"
x-collection-name: Baltimore Open311
x-complete: 1
info:
  title: Open311 GeoReport API
  description: open311-allows-you-to-getpost-civic-information-of-cities-via-a-unified-interface--the-georeport-part-allows-you-to-submit-and-view-issues-at-the-public-local-space
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