---
swagger: "2.0"
x-collection-name: RipaEx
x-complete: 0
info:
  title: RipaEx Signatures Fee
  description: Get the fee for a signature.
  version: 1.0.0
host: api.ripaex.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/signatures/fee:
    get:
      summary: Signatures Fee
      description: Get the fee for a signature.
      operationId: signatures.fee
      x-api-path-slug: apisignaturesfee-get
      parameters:
      - in: query
        name: address
        description: A valid RIPA Address
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Signatures
      - Fee
  /api/signatures:
    put:
      summary: Signatures
      description: Create a new signature.
      operationId: signatures.addSignature
      x-api-path-slug: apisignatures-put
      parameters:
      - in: body
        name: body
        description: A valid signature object
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Signatures
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