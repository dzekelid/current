---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
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
  /api/property/{id}/tenantroles:
    get:
      summary: Get a list of all current and ended tenant roles from a property id.
      description: Get a list of all current and ended tenant roles from a property
        id..
      operationId: Property_TenantRolesByPropertyIdByid
      x-api-path-slug: apipropertyidtenantroles-get
      parameters:
      - in: path
        name: id
        description: The Id of the property
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - ""
      - Current
      - Ended
      - Tenant
      - Roles
      - From
      - Property
      - Id
  /api/reconcile/save:
    put:
      summary: Save current reconcile progress
      description: Save current reconcile progress.
      operationId: Reconcile_SaveByreconcileDataContract
      x-api-path-slug: apireconcilesave-put
      parameters:
      - in: body
        name: reconcileDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Save
      - Current
      - Reconcile
      - Progress
  /api/role/{id}/offers:
    get:
      summary: Get all of the offers associated to the current property marketing
        role.
      description: Get all of the offers associated to the current property marketing
        role..
      operationId: Role_OffersByidBypageSizeBypageNumberByexcludeDrafts
      x-api-path-slug: apiroleidoffers-get
      parameters:
      - in: query
        name: excludeDrafts
      - in: path
        name: id
        description: The id of the role to get the offers for
      - in: query
        name: pageNumber
        description: Page number to return
      - in: query
        name: pageSize
        description: Page size to return
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Of
      - Offers
      - Associated
      - To
      - Current
      - Property
      - Marketing
      - Role
  /api/role/{id}/offersbasic:
    get:
      summary: Get a basic list of offers associated to the current property marketing
        role.
      description: Get a basic list of offers associated to the current property marketing
        role..
      operationId: Role_OffersBasicByid
      x-api-path-slug: apiroleidoffersbasic-get
      parameters:
      - in: path
        name: id
        description: The id of the marketing role to get the offers for
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Basic
      - List
      - Of
      - Offers
      - Associated
      - To
      - Current
      - Property
      - Marketing
      - Role
  /api/role/{id}/viewings:
    get:
      summary: Get all of the viewings associated to the current property marketing
        role.
      description: Get all of the viewings associated to the current property marketing
        role..
      operationId: Role_ViewingsByidBypageSizeBypageNumberByexcludeDrafts
      x-api-path-slug: apiroleidviewings-get
      parameters:
      - in: query
        name: excludeDrafts
      - in: path
        name: id
        description: The id of the role to get the offers for
      - in: query
        name: pageNumber
        description: Page number to return
      - in: query
        name: pageSize
        description: Page size to return
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Of
      - Viewings
      - Associated
      - To
      - Current
      - Property
      - Marketing
      - Role
  /api/roomdescription/{id}/uploadandattachdocumenttoroom:
    put:
      summary: Uploads and attaches a document to room description room - the new
        document is appended to the current list.
      description: Uploads and attaches a document to room description room - the
        new document is appended to the current list..
      operationId: RoomDescription_UploadAndAttachDocumentToRoomByidByroomIdBydocumentDetails
      x-api-path-slug: apiroomdescriptioniduploadandattachdocumenttoroom-put
      parameters:
      - in: body
        name: documentDetails
        description: Details about the document
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The room description Id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: roomId
        description: The roomId
      responses:
        200:
          description: OK
      tags:
      - Uploads
      - Attaches
      - Document
      - To
      - Room
      - Description
      - Room
      - '-'
      - New
      - Document
      - Is
      - Appended
      - To
      - Current
      - List
  /api/property/{id}/addgrouptoproperty:
    put:
      summary: Creates/Adds a group to the CurrentOwners of the supplied PropertyId
      description: Creates/adds a group to the currentowners of the supplied propertyid.
      operationId: Property_AddGroupToPropertyByidBydatacontract
      x-api-path-slug: apipropertyidaddgrouptoproperty-put
      parameters:
      - in: body
        name: datacontract
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The property id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Creates
      - S
      - Group
      - To
      - CurrentOwners
      - Of
      - Supplied
      - PropertyId
---