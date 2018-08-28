---
swagger: "2.0"
x-collection-name: PagerDuty
x-complete: 1
info:
  title: PagerDuty
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /incidents/{id}/snooze:
    post:
      summary: Snooze an incident
      description: Post incents  snooze
      operationId: snooze-an-incident
      x-api-path-slug: incidentsidsnooze-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: payload
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Incident Snooze
---