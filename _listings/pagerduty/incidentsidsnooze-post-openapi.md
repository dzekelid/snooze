---
swagger: "2.0"
x-collection-name: PagerDuty
x-complete: 0
info:
  title: PagerDuty Snooze an incident
  version: 1.0.0
  description: Post incents  snooze
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