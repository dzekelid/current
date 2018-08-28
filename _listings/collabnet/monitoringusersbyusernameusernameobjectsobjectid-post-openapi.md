---
swagger: "2.0"
x-collection-name: CollabNet
x-complete: 0
info:
  title: CollabNet TeamForge API Documentation Monitors the current object for the
    given username.
  version: 1.0.0
  description: Monitors the current object for the given username..
basePath: /ctfrest/foundation/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/myself/projects/{projectid}:
    put:
      summary: Adds current user to specified project's member list
      description: Adds current user to specified project's member list.
      operationId: addMyself
      x-api-path-slug: usersmyselfprojectsprojectid-put
      parameters:
      - in: path
        name: projectid
        description: Project id
      responses:
        200:
          description: OK
      tags:
      - Current
      - User
      - To
      - Specified
      - Projects
      - Member
      - List
  /users/myself/projects:
    get:
      summary: Gets current user's project list
      description: Gets current user's project list.
      operationId: getMyProjects
      x-api-path-slug: usersmyselfprojects-get
      parameters:
      - in: query
        name: fetchHierarchyPath
      - in: query
        name: sortby
        description: Sort by column name
      responses:
        200:
          description: OK
      tags:
      - Current
      - Users
      - Project
      - List
  /users/myself/groups/{groupid}:
    put:
      summary: Add current user to a user group
      description: Add current user to a user group.
      operationId: addMyselfToGroup
      x-api-path-slug: usersmyselfgroupsgroupid-put
      parameters:
      - in: path
        name: groupid
        description: Group id
      responses:
        200:
          description: OK
      tags:
      - Current
      - User
      - To
      - User
      - Group
  /users/myself/groups:
    get:
      summary: Gets current user's group list
      description: Gets current user's group list.
      operationId: getMyUserGroups
      x-api-path-slug: usersmyselfgroups-get
      responses:
        200:
          description: OK
      tags:
      - Current
      - Users
      - Group
      - List
  /users/myself:
    patch:
      summary: Updates current user data
      description: Updates current user data.
      operationId: updateMyself
      x-api-path-slug: usersmyself-patch
      parameters:
      - in: body
        name: body
        description: Updated user info
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: If-Match
        description: User version
      responses:
        200:
          description: OK
      tags:
      - Current
      - User
      - Data
  /myself/recent/projects:
    get:
      summary: Gets recent project list for the current user
      description: Gets recent project list for the current user.
      operationId: getMyRecentProjects
      x-api-path-slug: myselfrecentprojects-get
      parameters:
      - in: query
        name: count
        description: Max
      responses:
        200:
          description: OK
      tags:
      - Recent
      - Project
      - Listthe
      - Current
      - User
  /myself/recent/objects:
    get:
      summary: Gets recent object list for the current user
      description: Gets recent object list for the current user.
      operationId: getMyRecentObjects
      x-api-path-slug: myselfrecentobjects-get
      parameters:
      - in: query
        name: count
        description: Max
      responses:
        200:
          description: OK
      tags:
      - Recent
      - Object
      - Listthe
      - Current
      - User
  /monitoring/users/{userid}/objects/{objectid}:
    delete:
      summary: UnMonitors the current object for given userid
      description: Unmonitors the current object for given userid.
      operationId: unMonitorObjectByid
      x-api-path-slug: monitoringusersuseridobjectsobjectid-delete
      parameters:
      - in: path
        name: objectid
        description: Object id
      - in: path
        name: userid
        description: User id
      responses:
        200:
          description: OK
      tags:
      - UnMonitors
      - Current
      - Objectgiven
      - Userid
    post:
      summary: Monitors the current object for the given userid.
      description: Monitors the current object for the given userid..
      operationId: monitorObjectByUserid
      x-api-path-slug: monitoringusersuseridobjectsobjectid-post
      parameters:
      - in: path
        name: objectid
        description: Object id
      - in: path
        name: userid
        description: User id
      responses:
        200:
          description: OK
      tags:
      - Monitors
      - Current
      - Objectthe
      - Given
      - Userid
    get:
      summary: Monitoring the current object or not for the given user id (true /
        false)
      description: Monitoring the current object or not for the given user id (true
        / false).
      operationId: isObjectMonitoredByUserid
      x-api-path-slug: monitoringusersuseridobjectsobjectid-get
      parameters:
      - in: path
        name: objectid
        description: Object id
      - in: path
        name: userid
        description: User id
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Current
      - Object
      - Notthe
      - Given
      - User
      - (true
      - ""
      - ""
      - False)
  /monitoring/users/myself/objects/{objectid}:
    delete:
      summary: UnMonitors the current object for the current user,
      description: Unmonitors the current object for the current user,.
      operationId: unMonitorObject
      x-api-path-slug: monitoringusersmyselfobjectsobjectid-delete
      parameters:
      - in: path
        name: objectid
        description: Object id
      responses:
        200:
          description: OK
      tags:
      - UnMonitors
      - Current
      - Objectthe
      - Current
      - User
      - ""
    post:
      summary: Monitors the current object for current user.
      description: Monitors the current object for current user..
      operationId: monitorObjectForUser
      x-api-path-slug: monitoringusersmyselfobjectsobjectid-post
      parameters:
      - in: path
        name: objectid
        description: Object id
      responses:
        200:
          description: OK
      tags:
      - Monitors
      - Current
      - Objectcurrent
      - User
    get:
      summary: The logged in user is monitoring the current object or not (true /
        false)
      description: The logged in user is monitoring the current object or not (true
        / false).
      operationId: isObjectMonitored
      x-api-path-slug: monitoringusersmyselfobjectsobjectid-get
      parameters:
      - in: path
        name: objectid
        description: Object id
      responses:
        200:
          description: OK
      tags:
      - The
      - Logged
      - In
      - User
      - Is
      - Monitoring
      - Current
      - Object
      - Not
      - (true
      - ""
      - ""
      - False)
  /monitoring/users/by-username/{username}/objects/{objectid}:
    delete:
      summary: UnMonitors the current object for the given username.
      description: Unmonitors the current object for the given username..
      operationId: unMonitorObjectByuser
      x-api-path-slug: monitoringusersbyusernameusernameobjectsobjectid-delete
      parameters:
      - in: path
        name: objectid
        description: Object id
      - in: path
        name: username
        description: Username
      responses:
        200:
          description: OK
      tags:
      - UnMonitors
      - Current
      - Objectthe
      - Given
      - Username
    post:
      summary: Monitors the current object for the given username.
      description: Monitors the current object for the given username..
      operationId: monitorObjectByUsername
      x-api-path-slug: monitoringusersbyusernameusernameobjectsobjectid-post
      parameters:
      - in: path
        name: objectid
        description: Object id
      - in: path
        name: username
        description: Username
      responses:
        200:
          description: OK
      tags:
      - Monitors
      - Current
      - Objectthe
      - Given
      - Username
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