---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Event Snooze Reminder
  description: 'event: snoozeReminder Postpone a reminder until a new time.'
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /me/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: meeventsidsnoozereminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Snooze
      - Reminder
  /users/{id | userPrincipalName}/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: usersid--userprincipalnameeventsidsnoozereminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Snooze
      - Reminder
  /groups/{id}/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: groupsideventsidsnoozereminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Snooze
      - Reminder
  /me/calendar/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: mecalendareventsidsnoozereminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Snooze
      - Reminder
  /users/{id | userPrincipalName}/calendar/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: usersid--userprincipalnamecalendareventsidsnoozereminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Snooze
      - Reminder
  /groups/{id}/calendar/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: groupsidcalendareventsidsnoozereminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Snooze
      - Reminder
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