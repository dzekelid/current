swagger: "2.0"
x-collection-name: Square
x-complete: 1
info:
  title: Square Connect
  description: client-library-for-accessing-the-square-connect-apis
  termsOfService: https://connect.squareup.com/tos
  contact:
    name: Square Developer Platform
    url: https://squareup.com/developers
    email: developers@squareup.com
  version: "2.0"
host: connect.squareup.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/{location_id}/inventory/{variation_id}:
    post:
      summary: Adjusts an item variation's current available inventory.
      description: Adjusts an item variation's current available inventory.
      operationId: AdjustInventory
      x-api-path-slug: v1location-idinventoryvariation-id-post
      parameters:
      - in: body
        name: body
        description: An object containing the fields to POST for the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: location_id
        description: The ID of the items associated location
      - in: path
        name: variation_id
        description: The ID of the variation to adjust inventory information for
      responses:
        200:
          description: OK
      tags:
      - Adjusts
      - Item
      - Variations
      - Current
      - Available
      - Inventory