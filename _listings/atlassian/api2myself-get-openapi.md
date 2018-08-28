---
swagger: "2.0"
x-collection-name: Atlassian
x-complete: 0
info:
  title: Jira Cloud API Get current user
  description: |-
    Returns currently logged user. This resource cannot be accessed anonymously.

    The resource accepts the `expand` param that is used to include, hidden by default, parts of response. This can be used to include:

    *   `groups` \- all groups, including nested groups, to which user belongs
    *   `applicationRoles` \- application roles defines to which application user has access
  termsOfService: http://atlassian.com/terms/
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /user/current:
    get:
      summary: Get current user
      description: "Returns the currently logged-in user. This includes information
        about\nthe user, like the display name, userKey, account ID, profile picture,\nand
        more.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw) required**:
        \nPermission to access the Confluence site ('Can use' global permission)."
      operationId: com.atlassian.confluence.plugins.restapi.resources.UserResource.getCurrentUser_get
      x-api-path-slug: usercurrent-get
      parameters:
      - in: query
        name: expand
        description: A multi-value parameter indicating which properties of the user
          toexpand
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
        "":
          description: ""
        400:
          description: Bad input parameter
        401:
          description: Bad or expired token
        403:
          description: Bad OAuth request (wrong consumer key, bad nonce, expired timestamp
        404:
          description: File or folder not found at the specified path
        405:
          description: Request method not expected (generally should be GET or POST)
        429:
          description: Your app is making too many requests and is being rate limited
        503:
          description: If the response includes the Retry-After header, this means
            your OAuth 1
        507:
          description: User is over Dropbox storage quota
        5xx:
          description: Server error
        200:
          description: OK
      tags:
      - Current
      - User
  /api/2/myself:
    get:
      summary: Get current user
      description: |-
        Returns currently logged user. This resource cannot be accessed anonymously.

        The resource accepts the `expand` param that is used to include, hidden by default, parts of response. This can be used to include:

        *   `groups` \- all groups, including nested groups, to which user belongs
        *   `applicationRoles` \- application roles defines to which application user has access
      operationId: com.atlassian.jira.rest.v2.issue.CurrentUserResource.getCurrentUser_get
      x-api-path-slug: api2myself-get
      responses:
        200:
          description: OK
      tags:
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