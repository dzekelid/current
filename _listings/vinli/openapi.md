---
swagger: "2.0"
x-collection-name: Vinli
x-complete: 1
info:
  title: Vinli
  description: todo-add-description
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
---