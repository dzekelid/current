swagger: "2.0"
x-collection-name: Pivotal Tracker
x-complete: 1
info:
  title: Pivotal Tracker
  description: access-and-manipulate-agile-project-management-data-including-projects-stories-and-tasks-
  version: 1.0.0
host: www.pivotaltracker.com
basePath: /services/v3/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /projects/{PROJECT_ID}/iterations/current:
    get:
      summary: Get Projects Project Iterations Current
      description: Retrieves iterations from the "current" group, with stories.
      operationId: getProjectsProjectIterationsCurrent
      x-api-path-slug: projectsproject-iditerationscurrent-get
      parameters:
      - in: path
        name: PROJECT_ID
        description: The ID of the project
      responses:
        200:
          description: OK
      tags:
      - Projects
      - PROJECT
      - ID
      - Iterations
      - Current
  /projects/{PROJECT_ID}/iterations/current_backlog:
    get:
      summary: Get Projects Project Iterations Current Backlog
      description: Retrieves iterations from the "current" and "backlog" groups, with
        stories.
      operationId: getProjectsProjectIterationsCurrentBacklog
      x-api-path-slug: projectsproject-iditerationscurrent-backlog-get
      parameters:
      - in: query
        name: limit
        description: Controls the maximum number of iterations returned
      - in: query
        name: offset
        description: Controls the number of iterations to skip from the beginning
          of the result
      - in: path
        name: PROJECT_ID
        description: The ID of the project
      responses:
        200:
          description: OK
      tags:
      - Projects
      - PROJECT
      - ID
      - Iterations
      - Current
      - Backlog