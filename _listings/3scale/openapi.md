swagger: "2.0"
x-collection-name: 3scale
x-complete: 1
info:
  title: 3scale Service Management API
  description: the-api-for-managing-3scale-services-
  termsOfService: http://www.3scale.net/terms-and-conditions/
  contact:
    name: 3Scale
    url: https://support.3scale.net/
  version: "1"
host: su1.3scale.net
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