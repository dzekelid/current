swagger: "2.0"
x-collection-name: TelAPI
x-complete: 1
info:
  title: TelAPI
  description: telapi-is-a-rest-api--what-that-means-for-you-is-that-interacting-with-telapi-to-perform-all-of-your-telephony-needs-is-almost-as-simple-as-visiting-a-website--deeper-knowledge-regarding-rest-is-useful-when-developing-with-telapi-but-definitely-not-required--we-aim-to-provide-all-of-the-information-needed-for-working-with-our-rest-api-throughout-its-documentation-provided-here-so-even-if-you-are-new-to-rest-telapi-will-still-be-a-pleasure-to-use-
  termsOfService: http://www.telapi.com/legal/tos
  version: v2
host: api.telapi.com
basePath: v2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/hotel/v0/hotels/{hotelId}/rateplans/{rateplanCode}/rates:
    patch:
      summary: Partially update a rate of the specified rateplan for the defined time
        period.
      description: "The hetras API is using this Patch Specification\r\n            to
        partially update an existing resource. Currently this call only allows to
        set the base price for non-derived rateplans if the rateplan\r\n            is
        active and already loaded for the specified time period.\r\n            \r\n
        \           A request example:\r\n            [\r\n              {\r\n                \"op\":
        \"replace\", \"path\": \"/base_price\", \"value\": 120.00\r\n              }\r\n
        \           ]\r\n            \r\n            For more details on how the API
        responds to errors please check our documentation on \r\n            Error
        Handling."
      operationId: RatePlans_PatchRates
      x-api-path-slug: apihotelv0hotelshotelidrateplansrateplancoderates-patch
      parameters:
      - in: header
        name: App-Id
        description: Application identifier
      - in: header
        name: App-Key
        description: Application key
      - in: query
        name: from
        description: Defines the last business day you would like to get rates for
      - in: path
        name: hotelId
        description: The hotel id the rateplan belongs to
      - in: body
        name: patchRequest
        description: A set of JSON Patch operations
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: rateplanCode
        description: The code of the rateplan you want to update the daily rate details
          for
      - in: query
        name: to
        description: Defines the first business day you would like to get rates for
      responses:
        200:
          description: OK
      tags:
      - Partially
      - Update
      - Rate
      - Of
      - Specified
      - Rateplanthe
      - Defined
      - Time
      - Period
  /api/hotel/v0/hotels/{hotelId}/rateplans/{rateplanCode}/rates/{businessDay}:
    patch:
      summary: Partially update a rate of the specified rateplan for a defined business
        day.
      description: "The hetras API is using this Patch Specification\r\n            to
        partially update an existing resource. Currently this call only allows to
        set the base price for non-derived rateplans if the rateplan\r\n            is
        active and already loaded for the specified business day.\r\n            \r\n
        \           A request example:\r\n            [\r\n              {\r\n                \"op\":
        \"replace\", \"path\": \"/base_price\", \"value\": 120.00\r\n              }\r\n
        \           ]\r\n            \r\n            For more details on how the API
        responds to errors please check our documentation on \r\n            Error
        Handling."
      operationId: RatePlans_PatchRate
      x-api-path-slug: apihotelv0hotelshotelidrateplansrateplancoderatesbusinessday-patch
      parameters:
      - in: header
        name: App-Id
        description: Application identifier
      - in: header
        name: App-Key
        description: Application key
      - in: path
        name: businessDay
        description: The business day of the daily rate you want to update
      - in: path
        name: hotelId
        description: The hotel id the rateplan belongs to
      - in: body
        name: patchRequest
        description: A set of JSON Patch operations
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: rateplanCode
        description: The code of the rateplan you want to update the daily rate details
          for
      responses:
        200:
          description: OK
      tags:
      - Partially
      - Update
      - Rate
      - Of
      - Specified
      - Rateplana
      - Defined
      - Business
      - Day
  /api/hotel/v0/hotels/{hotelId}/rooms/{roomNumber}:
    patch:
      summary: Partially updates a room.
      description: "The hetras API is using this Patch Specification\r\n            to
        partially update an existing resource. Currently this call only allows to
        modify condition and housekeeping occupancy status of the room.\r\n            \r\n
        \           A request example:\r\n            [\r\n              {\r\n                \"op\":
        \"replace\", \"path\": \"/status/condition\", \"value\": \"CleanNotInspected\"\r\n
        \             }, {\r\n                \"op\": \"replace\", \"path\": \"/status/housekeeping_occupancy\",
        \"value\": \"Vacant\"\r\n              }\r\n            ]\r\n            \r\n
        \           For more details on how the API responds to errors please check
        our documentation on \r\n            Error Handling."
      operationId: Rooms_PatchRoom
      x-api-path-slug: apihotelv0hotelshotelidroomsroomnumber-patch
      parameters:
      - in: header
        name: App-Id
        description: Application identifier
      - in: header
        name: App-Key
        description: Application key
      - in: path
        name: hotelId
        description: The hotel id the room belongs to
      - in: body
        name: patchRequest
        description: A set of JSON Patch operations
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: roomNumber
        description: The room number of the room you would like to update
      responses:
        200:
          description: OK
      tags:
      - Partially
      - Updates
      - Room