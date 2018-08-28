swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 1
info:
  title: Microsoft Graph API
  description: microsoft-graph-exposes-multiple-apis-from-office-365-and-other-microsoft-cloud-services-through-a-single-endpoint-httpsgraph-microsoft-com--microsoft-graph-simplifies-queries-that-would-otherwise-be-more-complex-
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
  /me/calendars/{id}/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: mecalendarsideventsidsnoozereminder-post
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
  /users/{id | userPrincipalName}/calendars/{id}/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: usersid--userprincipalnamecalendarsideventsidsnoozereminder-post
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
  /me/calendargroup/calendars/{id}/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: mecalendargroupcalendarsideventsidsnoozereminder-post
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
  /users/{id | userPrincipalName}/calendargroup/calendars/{id}/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: usersid--userprincipalnamecalendargroupcalendarsideventsidsnoozereminder-post
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
  /me/calendargroups/{id}/calendars/{id}/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: mecalendargroupsidcalendarsideventsidsnoozereminder-post
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
  /users/{id | userPrincipalName}/calendargroups/{id}/calendars/{id}/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: usersid--userprincipalnamecalendargroupsidcalendarsideventsidsnoozereminder-post
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