---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 1
info:
  title: Xignite Global Real Time Options
  description: complete-stock-option-management-application-
  version: 1.0.0
host: globalrealtimeoptions.xignite.com
basePath: xglobalrealtimeoptions.json/XigniteGlobalRealTimeOptions
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /GetBlackScholesOptionValue:
    get:
      summary: Get Black Scholes Option Value
      description: Calculates the value of an option using the Black-Scholes formula.
      operationId: GetBlackScholesOptionValue
      x-api-path-slug: getblackscholesoptionvalue-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Black
      - Scholes
      - Option
      - Value
---