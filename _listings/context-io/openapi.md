---
swagger: "2.0"
x-collection-name: Context.IO
x-complete: 1
info:
  title: Context.IO
  description: context-io-is-the-missing-email-api-that-makes-it-easy-and-fast-to-integrate-your-users-email-data-in-your-application-
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
---