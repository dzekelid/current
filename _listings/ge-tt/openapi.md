swagger: "2.0"
x-collection-name: Ge.tt
x-complete: 1
info:
  title: Ge.tt  REST API
  description: the-ge-tt-api-allows-you-to-use-ge-tt-in-your-own-applications--we-believe-that-our-users-should-be-able-to-access-their-files-and-share-their-content-in-their-platform-of-choice--by-using-the-api-developers-are-able-to-easily-put-their-own-content-or-the-content-of-their-users-online--at-the-same-time-they-are-able-to-use-ge-tts-unique-realtime-file-sharing-technology-where-files-are-available-before-they-are-even-uploaded-
  termsOfService: http://ge.tt/terms
  version: "1"
host: open.ge.tt
basePath: /1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /1/files/{sharename}/{fileid}/blob/thumb:
    get:
      summary: Files  Blob Thumb
      description: Will redirect to a thumbnail of the binary file. Currently only
        available for images.
      operationId: get1FilesSharenameFileBlobThumb
      x-api-path-slug: 1filessharenamefileidblobthumb-get
      parameters:
      - in: path
        name: fileid
      - in: path
        name: sharename
      responses:
        200:
          description: OK
      tags:
      - Files
      - Sharename
      - Fileid
      - Blob
      - Thumb
  /1/shares/{sharename}/update:
    post:
      summary: Shares Update
      description: Updates a share. Currently you can only update the title
      operationId: post1SharesSharenameUpdate
      x-api-path-slug: 1sharessharenameupdate-post
      parameters:
      - in: query
        name: accesstoken
      - in: path
        name: sharename
      responses:
        200:
          description: OK
      tags:
      - Shares
      - Sharename
      - Update