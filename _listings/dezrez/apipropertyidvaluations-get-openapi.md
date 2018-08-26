---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Get all of the valuations associated to the current owner of the property.
  version: 1.0.0
  description: Get all of the valuations associated to the current owner of the property..
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/agency/getvatrate:
    get:
      summary: Gets the current VAT rate unless the date is specified
      description: Gets the current vat rate unless the date is specified.
      operationId: Agency_GetVatRateByvatRateTypeByvatDate
      x-api-path-slug: apiagencygetvatrate-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: vatDate
        description: Date of VAT value, used to get historic or future VAT Rates
      - in: query
        name: vatRateType
        description: Vat Rate type, standard is currently option
      responses:
        200:
          description: OK
      tags:
      - S
      - Current
      - VAT
      - Rate
      - Unless
      - Date
      - Is
      - Specified
  /api/Agency:
    get:
      summary: Get details of the current users agency
      description: Get details of the current users agency.
      operationId: Agency_Get
      x-api-path-slug: apiagency-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Details
      - Of
      - Current
      - Users
      - Agency
  /api/coreplatformstate/sendpendingalerts:
    post:
      summary: Sends alerts for all current platform issues.
      description: Sends alerts for all current platform issues..
      operationId: CorePlatformState_SendPendingAlerts
      x-api-path-slug: apicoreplatformstatesendpendingalerts-post
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Sends
      - Alerts
      - Current
      - Platform
      - Issues
  /api/property/{id}/owners/events:
    get:
      summary: Get property events for the current owner by its Id
      description: Get property events for the current owner by its id.
      operationId: Property_OwnersEventsByidBypageSizeBypageNumberBybranchIdByfromBytoBytypeByeventCategoryType
      x-api-path-slug: apipropertyidownersevents-get
      parameters:
      - in: query
        name: branchId
      - in: query
        name: eventCategoryType
        description: An event category type to return
      - in: query
        name: from
        description: the date from
      - in: path
        name: id
        description: The id of the property to get events for
      - in: query
        name: pageNumber
        description: The page of events to return
      - in: query
        name: pageSize
        description: The number of events to return
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: to
        description: the date to
      - in: query
        name: type
        description: The event type to get
      responses:
        200:
          description: OK
      tags:
      - Property
      - Eventsthe
      - Current
      - Owner
      - By
      - Its
      - Id
  /api/property/{id}/valuations:
    get:
      summary: Get all of the valuations associated to the current owner of the property.
      description: Get all of the valuations associated to the current owner of the
        property..
      operationId: Property_ValuationsByidBypageSizeBypageNumber
      x-api-path-slug: apipropertyidvaluations-get
      parameters:
      - in: path
        name: id
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Of
      - Valuations
      - Associated
      - To
      - Current
      - Owner
      - Of
      - Property
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