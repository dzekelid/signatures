swagger: "2.0"
x-collection-name: AMEE
x-complete: 1
info:
  title: AMEE WRI Aqueduct API
  version: 1.0.0
host: api.roaring.io
basePath: /company/1.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /company-signatory:
    get:
      summary: Get Company Signatory
      description: Get company signatory.
      operationId: getCompanySignatory
      x-api-path-slug: companysignatory-get
      parameters:
      - in: query
        name: companyId
        description: Company identification for the company
      - in: query
        name: countryCode
        description: Country code for the company
      responses:
        200:
          description: OK
      tags:
      - Company
      - Signatory
    post:
      summary: Post Company Signatory
      description: Post company signatory.
      operationId: postCompanySignatory
      x-api-path-slug: companysignatory-post
      parameters:
      - in: body
        name: body
        description: Request body with company identifiers to lookup
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: countryCode
        description: Country code for the company
      responses:
        200:
          description: OK
      tags:
      - Company
      - Signatory