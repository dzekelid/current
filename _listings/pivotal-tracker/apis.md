---
name: Pivotal Tracker
x-slug: pivotal-tracker
description: Pivotal Tracker is the agile project management tool of choice for developers
  around the world for real-time collaboration around a shared, prioritized backlog.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11526-pivotal-tracker.jpg
x-kinRank: "7"
x-alexaRank: "15894"
tags: Current
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/pivotal-tracker/apis.md
specificationVersion: "0.14"
apis:
- name: Pivotal Tracker Get Projects Project Iterations Current
  x-api-slug: pivotal-tracker
  description: Retrieves iterations from the "current" group, with stories.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11526-pivotal-tracker.jpg
  humanURL: http://pivotaltracker.com
  baseURL: https://www.pivotaltracker.com//services/v3///projects/{PROJECT_ID}/iterations/current
  tags: Projects,PROJECT,ID,Iterations,Current
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/pivotal-tracker/projectsproject-iditerationscurrent-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/pivotal-tracker/projectsproject-iditerationscurrent-get-openapi.md
- name: Pivotal Tracker Get Projects Project Iterations Current Backlog
  x-api-slug: pivotal-tracker
  description: Retrieves iterations from the "current" and "backlog" groups, with
    stories.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11526-pivotal-tracker.jpg
  humanURL: http://pivotaltracker.com
  baseURL: https://www.pivotaltracker.com//services/v3///projects/{PROJECT_ID}/iterations/current_backlog
  tags: Projects,PROJECT,ID,Iterations,Current,Backlog
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/pivotal-tracker/projectsproject-iditerationscurrent-backlog-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/pivotal-tracker/projectsproject-iditerationscurrent-backlog-get-openapi.md
- name: Pivotal Tracker
  x-api-slug: pivotal-tracker
  description: Whether welding together two apps or forging a unique one, tap into
    100% of the Tracker feature set with the very same API the Tracker team uses.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11526-pivotal-tracker.jpg
  humanURL: http://pivotaltracker.com
  baseURL: https://www.pivotaltracker.com//services/v3/
  tags: Current
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/pivotal-tracker/openapi.md
x-common:
- type: x-blog
  url: http://www.pivotaltracker.com/community/tracker-blog
- type: x-blog
  url: http://www.pivotaltracker.com/feed
- type: x-crunchbase
  url: https://crunchbase.com/organization/pivotaltracker
- type: x-email
  url: TRACKER@PIVOTAL.IO
- type: x-faq
  url: https://www.pivotaltracker.com/faq
- type: x-github
  url: https://github.com/pivotal
- type: x-linkedin
  url: https://www.linkedin.com/showcase/pivotal-tracker/
- type: x-pricing
  url: http://www.pivotaltracker.com/why-tracker/pricing
- type: x-selfservice-registration
  url: https://www.pivotaltracker.com/signup/new
- type: x-status
  url: http://status.pivotaltracker.com/
- type: x-terms-of-service
  url: https://www.pivotaltracker.com/policy/eula
- type: x-twitter
  url: https://twitter.com/pivotaltracker
- type: x-website
  url: http://pivotaltracker.com
- type: x-website
  url: http://www.pivotaltracker.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---