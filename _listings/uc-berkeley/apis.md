---
name: UC Berkeley
x-slug: uc-berkeley
description: Founded in 1868, the University of California, Berkeley is one of the
  worlds preeminent public universities, boasting a distinguished faculty (with 22
  Nobel laureates to date), stellar research libraries, and more than 350 academic
  programs. At the he...
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/270-uc-berkeley.jpg
x-kinRank: "9"
x-alexaRank: "906"
tags: Current
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/uc-berkeley/apis.md
specificationVersion: "0.14"
apis:
- name: UC Berkeley Academic Terms API Current Academic Term
  x-api-slug: uc-berkeley-academic-terms-api
  description: Get the current academic term.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/270-uc-berkeley.jpg
  humanURL: https://api-central.berkeley.edu/
  baseURL: https://apis.berkeley.edu//sisconnect//GetAcademicCurrentTerm
  tags: Current,Academic,Term
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/uc-berkeley/getacademiccurrentterm-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/uc-berkeley/getacademiccurrentterm-get-openapi.md
- name: UC Berkeley Academic Terms API
  x-api-slug: uc-berkeley-academic-terms-api
  description: This API uses the current date to calculate the current and coming
    years academic terms. For the current term resource it returns the term code and
    term year. For the next terms resource it returns a set of terms that each include
    a term title, the combined year and code, and the code and year separately.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/270-uc-berkeley.jpg
  humanURL: https://api-central.berkeley.edu/
  baseURL: https://apis.berkeley.edu//sisconnect
  tags: Current
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/uc-berkeley/openapi.md
x-common:
- type: x-crunchbase
  url: http://www.crunchbase.com/company/university-of-california-berkeley
- type: x-crunchbase
  url: https://crunchbase.com/organization/university-of-california-berkeley
- type: x-email
  url: webmaster@berkeley.edu
- type: x-twitter
  url: https://twitter.com/UCBerkeley
- type: x-website
  url: https://api-central.berkeley.edu/
- type: x-website
  url: http://berkeley.edu
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---