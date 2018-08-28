swagger: "2.0"
x-collection-name: Steem
x-complete: 1
info:
  title: Interactive Steem API
  description: interactive-steem-api-lets-you-interact-with-steem-blockchain-and-make-a-request-get-output-and-start-implementing-new-apps-apis-have-default-parameters-set-to-get-you-started-and-see-how-request-works--api-list-is-compiled-from-steem-githubhttpsgithub-comsteemitsteem-1httpsgithub-comsteemitsteemtreemasterlibrariesappincludesteemitappapi-hpp-and-2httpsgithub-comsteemitsteemtreemasterlibrariesappincludesteemitappdatabase-api-hpp--if-you-want-to-contribute-documenting-detail-of-properties-and-output-contact-goodkarmahttpssteemit-chatdirectgoodkarma--you-can-also-check-full-list-here-steem-jshttpssteemjs-com
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