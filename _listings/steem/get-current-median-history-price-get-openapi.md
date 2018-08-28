---
swagger: "2.0"
x-collection-name: Steem
x-complete: 0
info:
  title: Steem get_current_median_history_price
  description: get_current_median_history_price
  version: 1.0.0
host: api.steemjs.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /get_current_median_history_price:
    get:
      summary: get_current_median_history_price
      description: get_current_median_history_price
      operationId: get-current-median-history-price
      x-api-path-slug: get-current-median-history-price-get
      responses:
        200:
          description: OK
      tags:
      - Get
      - Current
      - Median
      - History
      - Price
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