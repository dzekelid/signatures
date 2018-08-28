swagger: "2.0"
x-collection-name: RipaEx
x-complete: 1
info:
  title: RIPA Node Documentation
  description: this-is-a-documentation-for-ripanodehttpsgithub-comripaexripanode-built-with-swagger-ui-to-make-testing-a-breeze--if-you-find-any-issues-come-over-to-ripaexripanodetestapihttpsgithub-comripaexripanodetestapi-to-open-an-issue-or-even-better-send-a-pr-that-fixes-the-issue-the-community-ssl-public-api-used-as-test-host-is-provided-from-ripaex-iohttpswww-ripaex-io-
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