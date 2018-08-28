---
swagger: "2.0"
x-collection-name: Context.IO
x-complete: 0
info:
  title: Context.IO Get Accounts Files Fileid Related
  description: Lists other files related to a given file. Returns a list of files
    that are related to the given file. Currently, relation between files is based
    on how similar their names are.
  version: 1.0.0
host: api.context.io
basePath: /2.0/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /accounts/{id}/files/{fileId}/related:
    get:
      summary: Get Accounts Files Fileid Related
      description: Lists other files related to a given file. Returns a list of files
        that are related to the given file. Currently, relation between files is based
        on how similar their names are.
      operationId: listAccountFileRelatedFiles_
      x-api-path-slug: accountsidfilesfileidrelated-get
      parameters:
      - in: path
        name: fileId
        description: Unique id of a file
      - in: path
        name: id
        description: Unique id of an account accessible through your API key
      responses:
        200:
          description: OK
      tags:
      - Accounts
      - Files
      - FileId
      - Related
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