---
swagger: "2.0"
x-collection-name: BetterDoctor
x-complete: 1
info:
  title: BetterDoctor
  description: betterdoctor-helps-people-find-and-connect-to-the-best-doctors-through-our-consumer-app-doctor-marketing-services-and-api--our-mission-is-to-help-increase-transparency-in-healthcare-and-help-consumers-make-better-decisions-
  version: 1.0.0
host: api.betterdoctor.com
basePath: /2016-03-01
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /insurances:
    get:
      summary: Retrieve insurance providers and plans
      description: Insurance provider & plan list
      operationId: insurance-provider--plan-list
      x-api-path-slug: insurances-get
      parameters:
      - in: query
        name: fields
        description: A comma-separated list of fields to include
      - in: query
        name: limit
        description: For paginated list operations; specifies the maximum number of
          items to retrieve
      - in: query
        name: skip
        description: For paginated list operations; specifies the zero-based start
          index of the first item to retrieve
      - in: query
        name: user_key
        description: Your API access key
      responses:
        200:
          description: OK
      tags:
      - Insurance
---