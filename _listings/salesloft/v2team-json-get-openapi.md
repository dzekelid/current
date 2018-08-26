---
swagger: "2.0"
x-collection-name: SalesLoft
x-complete: 0
info:
  title: SalesLoft Fetch current team
  description: Fetches the team of the authenticated user.
  version: v2
host: api.salesloft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v2/me.json:
    get:
      summary: Fetch current user
      description: |-
        Authenticated user information. This endpoint does not accept any parameters as it is
        represents your authenticated user. The "Users" resource provides user information
        for other users on the team.
      operationId: v2.me.json.get
      x-api-path-slug: v2me-json-get
      responses:
        200:
          description: OK
      tags:
      - Sales
      - Fetch
      - Current
      - User
  /v2/team.json:
    get:
      summary: Fetch current team
      description: Fetches the team of the authenticated user.
      operationId: v2.team.json.get
      x-api-path-slug: v2team-json-get
      responses:
        200:
          description: OK
      tags:
      - Sales
      - Fetch
      - Current
      - Team
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