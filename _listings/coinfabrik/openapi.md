---
swagger: "2.0"
x-collection-name: CoinFabrik
x-complete: 1
info:
  title: Coinbase API
  description: the-coinbase-v2-api
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
    put:
      summary: Update current user
      description: Modify current user and their preferences.
      operationId: modify-current-user-and-their-preferences
      x-api-path-slug: user-put
      parameters:
      - in: body
        name: body
        description: Properties to update
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Current
      - User
---