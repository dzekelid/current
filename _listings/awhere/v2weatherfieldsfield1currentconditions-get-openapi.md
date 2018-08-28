---
swagger: "2.0"
x-collection-name: aWhere
x-complete: 0
info:
  title: aWhere Current Conditions
  description: |-
    ####Request
    This API call provides a snapshot of recent weather using the weather station nearest to the field location.

    [Current Conditions Documentation](http://developer.awhere.com/api/reference/weather/current)

    _Tip: Remember to use a field ID that exists in your account. By default, this collection uses a default field ID of 'field1'_


    ####Security
    This API call uses the security Access Token that is retrieved with the "Get a Token" request. If you run that request first, it will save a token to Postman and this API will use it automatically. You can also see where the token should normally go by clicking the "Headers" tab below. The Authorization header holds the token, replacing the "{{aWhereAccessToken}}" part.
  version: 1.0.0
host: api.awhere.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v2/weather/fields/field1/currentconditions:
    get:
      summary: Current Conditions
      description: |-
        ####Request
        This API call provides a snapshot of recent weather using the weather station nearest to the field location.

        [Current Conditions Documentation](http://developer.awhere.com/api/reference/weather/current)

        _Tip: Remember to use a field ID that exists in your account. By default, this collection uses a default field ID of 'field1'_


        ####Security
        This API call uses the security Access Token that is retrieved with the "Get a Token" request. If you run that request first, it will save a token to Postman and this API will use it automatically. You can also see where the token should normally go by clicking the "Headers" tab below. The Authorization header holds the token, replacing the "{{aWhereAccessToken}}" part.
      operationId: V2WeatherFieldsField1CurrentconditionsGet
      x-api-path-slug: v2weatherfieldsfield1currentconditions-get
      responses:
        200:
          description: OK
      tags:
      - Agriculture
      - Current
      - Conditions
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