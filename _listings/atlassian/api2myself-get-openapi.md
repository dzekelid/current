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