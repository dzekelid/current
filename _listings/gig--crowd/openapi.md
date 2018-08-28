swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 1
info:
  title: GIG & Crowd
  version: 1.0.0
host: gigandcrowd.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/city/current:
    get:
      summary: Get City Current
      description: Get city current.
      operationId: getApiV1CityCurrent
      x-api-path-slug: apiv1citycurrent-get
      responses:
        200:
          description: OK
      tags:
      - City
      - Current
  /api/v1/gigme/city/current:
    get:
      summary: Get Gigme City Current
      description: Get gigme city current.
      operationId: getApiV1GigmeCityCurrent
      x-api-path-slug: apiv1gigmecitycurrent-get
      responses:
        200:
          description: OK
      tags:
      - Gigme
      - City
      - Current