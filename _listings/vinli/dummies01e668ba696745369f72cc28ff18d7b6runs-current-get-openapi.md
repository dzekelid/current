---
swagger: "2.0"
x-collection-name: Vinli
x-complete: 0
info:
  title: Vinli Get Current Run
  description: Get current run.
  version: 1.0.0
host: events.vin.li
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /dummies/01e668ba-6967-4536-9f72-cc28ff18d7b6/runs/_current:
    get:
      summary: Get Current Run
      description: Get current run.
      operationId: Dummies01e668ba696745369f72Cc28ff18d7b6RunsCurrentGet
      x-api-path-slug: dummies01e668ba696745369f72cc28ff18d7b6runs-current-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Current
      - Run
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