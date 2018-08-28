swagger: "2.0"
x-collection-name: UC Berkeley
x-complete: 1
info:
  title: UC Berkeley
  version: 1.0.0
host: apis.berkeley.edu
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /GetAcademicCurrentTerm:
    get:
      summary: Current Academic Term
      description: Get the current academic term.
      operationId: getGetacademiccurrentterm
      x-api-path-slug: getacademiccurrentterm-get
      parameters:
      - in: header
        name: app_id
        description: App ID
      - in: header
        name: app_key
        description: App Key
      responses:
        1:
          description: Brand not found - Unable to find the given brand ID
        100:
          description: Invalid API Key - The API key passed was not valid or has expired
        105:
          description: Service currently unavailable - The requested service is temporarily
            unavailable
        106:
          description: Write operation failed - The requested operation failed due
            to a temporary issue
        111:
          description: Format "xxx" not found - The requested response format was
            not found
        112:
          description: Method "xxx" not found - The requested method was not found
        114:
          description: Invalid SOAP envelope - The SOAP envelope send in the request
            could not be parsed
        115:
          description: Invalid XML-RPC Method Call - The XML-RPC request document
            could not be parsed
        116:
          description: Bad URL found - One or more arguments contained a URL that
            has been used for abuse on Flickr
      tags:
      - Current
      - Academic
      - Term