---
swagger: "2.0"
x-collection-name: CoinFabrik
x-complete: 0
info:
  title: CoinFabrik Show current user
  description: "Get current user\u2019s public information. To get user\u2019s email
    or private information, use permissions wallet:user:email and wallet:user:read."
  contact:
    name: CoinFabrik
    url: http://www.coinfabrik.com/
  version: 1.0.0
host: api.coinbase.com
basePath: /v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /user:
    get:
      summary: Show current user
      description: "Get current user\u2019s public information. To get user\u2019s
        email or private information, use permissions wallet:user:email and wallet:user:read."
      operationId: get-current-users-public-information-to-get-users-email-or-private-information-use-permissions-walle
      x-api-path-slug: user-get
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Show
      - Current
      - User
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