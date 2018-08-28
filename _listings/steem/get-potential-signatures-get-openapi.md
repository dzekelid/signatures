---
swagger: "2.0"
x-collection-name: Steem
x-complete: 0
info:
  title: Steem get_potential_signatures
  description: get_potential_signatures
  version: 1.0.0
host: api.steemjs.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /get_required_signatures:
    get:
      summary: get_required_signatures
      description: get_required_signatures
      operationId: get-required-signatures
      x-api-path-slug: get-required-signatures-get
      parameters:
      - in: query
        name: availableKeys
        description: availableKeys
      - in: query
        name: trx
        description: transaction
      responses:
        200:
          description: OK
      tags:
      - Get
      - Required
      - Signatures
  /get_potential_signatures:
    get:
      summary: get_potential_signatures
      description: get_potential_signatures
      operationId: get-potential-signatures
      x-api-path-slug: get-potential-signatures-get
      parameters:
      - in: query
        name: trx
        description: transaction
      responses:
        200:
          description: OK
      tags:
      - Get
      - Potential
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