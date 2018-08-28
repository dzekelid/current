---
swagger: "2.0"
x-collection-name: 3scale
x-complete: 0
info:
  title: 3scale Current Roles
  description: ""
  version: "1.0"
host: 'http:'
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  //:
    get:
      summary: Current User
      description: Once a user has authorized a client to communicate on their behalf
        (via the `auth/authorize` endpoint), the client can use the generated token
        in their `x-client-bearer-token` header to retreive the user's information
        from this endpoint.
      operationId: UnnammedEndpointGet
      x-api-path-slug: get
      parameters:
      - in: header
        name: x-client-auth
      - in: header
        name: x-client-bearer-token
      responses:
        200:
          description: OK
      tags:
      - ""
  //{hostname}/auth/roles:
    get:
      summary: Current Roles
      description: ""
      operationId: AuthRolesByHostnameGet
      x-api-path-slug: hostnameauthroles-get
      parameters:
      - in: path
        name: hostname
      - in: header
        name: x-client-auth
      - in: header
        name: x-client-bearer-token
      responses:
        200:
          description: OK
      tags:
      - ""
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