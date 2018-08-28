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
  /api/negotiator/my/preferences/emailsignature:
    post:
      summary: Allows you to upload a document for use as email signature
      description: Allows you to upload a document for use as email signature.
      operationId: Negotiator_UploadEmailSignatureBydocumentDetailsContract
      x-api-path-slug: apinegotiatormypreferencesemailsignature-post
      parameters:
      - in: body
        name: documentDetailsContract
        description: Document details
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Allows
      - You
      - To
      - Upload
      - Documentuse
      - As
      - Email
      - Signature