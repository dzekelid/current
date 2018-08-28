---
swagger: "2.0"
x-collection-name: Coord
x-complete: 0
info:
  title: Coord Users API Retrieve the current user
  description: |-
    Retrieves information about the currently logged in user, including any associated profile
    information, vehicle information, and provisioned systems.

    The response will be the full User object:

    ```
      {
        "email": "user@domain.com",
        "vehicle": {
          "license_plate": {
            "text": "123abc",
            "country": "us",
            "subdivision": "ny"
          }
        }
        "transactable_systems": [
          {
            "system_id": "CitiBike",
            "linked_account": true
          }
        ]
      }
    ```
  version: 1.0.0
host: api.coord.co
basePath: /v1/users
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /user/current:
    get:
      summary: Retrieve the current user
      description: |-
        Retrieves information about the currently logged in user, including any associated profile
        information, vehicle information, and provisioned systems.

        The response will be the full User object:

        ```
          {
            "email": "user@domain.com",
            "vehicle": {
              "license_plate": {
                "text": "123abc",
                "country": "us",
                "subdivision": "ny"
              }
            }
            "transactable_systems": [
              {
                "system_id": "CitiBike",
                "linked_account": true
              }
            ]
          }
        ```
      operationId: get_user
      x-api-path-slug: usercurrent-get
      parameters:
      - in: query
        name: access_key
        description: The API access key for the request
      responses:
        200:
          description: OK
      tags:
      - Retrieve
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