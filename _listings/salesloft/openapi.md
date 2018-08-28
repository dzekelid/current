swagger: "2.0"
x-collection-name: SalesLoft
x-complete: 1
info:
  title: SalesLoft
  description: salesloft-helps-transform-sales-teams-into-modern-sales-organizations---converting-more-target-accounts-into-customer-accounts
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