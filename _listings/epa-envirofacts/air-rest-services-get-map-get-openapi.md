---
swagger: "2.0"
x-collection-name: EPA Envirofacts
x-complete: 0
info:
  title: U.S. EPA Enforcement and Compliance History Online (ECHO) - Clean Air Act
    Clean Air Act Map Service
  description: The purpose of the GET_MAP service is to display facility coordinates
    and facility clusters related to a get_facilities facility query. Currently, the
    maximum number of coordinates returned is 500. GET_MAP performs automatic clustering
    at the state, county, and zip code levels to maximize the number of coordinates
    returned.
  contact:
    name: US EPA, OECA Integration, Targeting and Access Branch
  version: 0.0.0
host: ofmpub.epa.gov
basePath: /echo
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /air_rest_services.get_map:
    get:
      summary: Clean Air Act Map Service
      description: The purpose of the GET_MAP service is to display facility coordinates
        and facility clusters related to a get_facilities facility query. Currently,
        the maximum number of coordinates returned is 500. GET_MAP performs automatic
        clustering at the state, county, and zip code levels to maximize the number
        of coordinates returned.
      operationId: the-purpose-of-the-get-map-service-is-to-display-facility-coordinates-and-facility-clusters-related-
      x-api-path-slug: air-rest-services-get-map-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Clean
      - Air
      - Act
      - Map
      - Service
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