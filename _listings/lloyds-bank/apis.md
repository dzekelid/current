---
name: Lloyds Bank
x-slug: lloyds-bank
description: Lloyds Bank plc is a British retail and commercial bank with branches
  across England and Wales. It has traditionally been considered one of the Big Four
  clearing banks. The bank was founded in Birmingham in 1765. It expanded during the
  nineteenth and twentieth centuries and took over a number of smaller banking companies.
  In 1995 it merged with the Trustee Savings Bank and traded as Lloyds TSB Bank plc
  between 1999 and 2013.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/lloyds_bank.png
x-kinRank: "7"
x-alexaRank: "4007"
tags: Current
created: "2018-08-26"
modified: "2018-08-26"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/lloyds-bank/apis.md
specificationVersion: "0.14"
apis:
- name: Lloyds Bank - Get Current Personal Accounts
  x-api-slug: personalcurrentaccounts-get
  description: This endpoint can contain multiple brands owned by a particular banking
    group. Each brand can own multiple PCA products.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/lloyds_bank.png
  humanURL: https://lloydsbank.com
  baseURL: https://api.lloydsbank.com/open-banking/v2.1/
  tags: Financial Services, UK Banks, API Provider, Profiles, Relative Data, General
    Data, Banking
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/lloyds-bank/personalcurrentaccounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/lloyds-bank/personalcurrentaccounts-get-openapi.md
- name: Lloyds Bank - Get Current Business Accounts
  x-api-slug: businesscurrentaccounts-get
  description: This endpoint can contain multiple brands owned by a particular banking
    group. Each brand can own multiple BCA products.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/lloyds_bank.png
  humanURL: https://lloydsbank.com
  baseURL: https://api.lloydsbank.com/open-banking/v2.1/
  tags: Financial Services, UK Banks, API Provider, Profiles, Relative Data, General
    Data, Banking
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/lloyds-bank/businesscurrentaccounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/lloyds-bank/businesscurrentaccounts-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://linkedin.api.gallery.streamdata.io
- type: x-api-stack
  url: http://lloyds.bank.stack.network
- type: x-crunchbase
  url: https://crunchbase.com/organization/lloyds-tsb-group
- type: x-developer
  url: https://developer.lloydsbank.com/
- type: x-documentation
  url: https://developer.lloydsbank.com/opendata-v2
- type: x-support
  url: https://developer.lloydsbank.com/faq-page
- type: x-terms-of-service
  url: https://developer.lloydsbank.com/terms
- type: x-twitter
  url: https://twitter.com/AskLloydsTSB
- type: x-website
  url: https://lloydsbank.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---