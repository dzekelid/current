---
name: HSBC
x-slug: hsbc
description: HSBC Holdings plc is a British multinational banking and financial services
  holding company, tracing its origin to a hong in Hong Kong. It is the worlds seventh
  largest bank by total assets and the largest in Europe with total assets of US$2.374
  trillion (as of December 2016). It was established in its present form in London
  in 1991 by The Hongkong and Shanghai Banking Corporation to act as a new group holding
  company. The origins of the bank lie mainly in Hong Kong and to a lesser extent
  in Shanghai, where branches were first opened in 1865. The HSBC name is derived
  from the initials of the Hongkong and Shanghai Banking Corporation. The company
  was first formally incorporated in 1866. The company continues to see both the United
  Kingdom and Hong Kong as its home markets.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/HSBC-Logo.png
x-kinRank: "8"
x-alexaRank: "8074"
tags: Current
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/hsbc/apis.md
specificationVersion: "0.14"
apis:
- name: HSBC Get Current Personal Accounts
  x-api-slug: hsbc
  description: This endpoint can contain multiple brands owned by a particular banking
    group. Each brand can own multiple PCA products.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/HSBC-Logo.png
  humanURL: https://hsbc.com
  baseURL: https://api.hsbc.com/open-banking/v2.1//personal-current-accounts/
  tags: Personal, Current, Accounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/hsbc/personalcurrentaccounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/hsbc/personalcurrentaccounts-get-openapi.md
- name: HSBC Get Current Business Accounts
  x-api-slug: hsbc
  description: This endpoint can contain multiple brands owned by a particular banking
    group. Each brand can own multiple BCA products.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/HSBC-Logo.png
  humanURL: https://hsbc.com
  baseURL: https://api.hsbc.com/open-banking/v2.1//business-current-accounts/
  tags: Business, Current, Accounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/hsbc/businesscurrentaccounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/hsbc/businesscurrentaccounts-get-openapi.md
- name: HSBC
  x-api-slug: hsbc
  description: HSBC Holdings plc is a British multinational banking and financial
    services holding company, tracing its origin to a hong in Hong Kong. It is the
    worlds seventh largest bank by total assets and the largest in Europe with total
    assets of US$2.374 trillion (as of December 2016). It was established in its present
    form in London in 1991 by The Hongkong and Shanghai Banking Corporation to act
    as a new group holding company. The origins of the bank lie mainly in Hong Kong
    and to a lesser extent in Shanghai, where branches were first opened in 1865.
    The HSBC name is derived from the initials of the Hongkong and Shanghai Banking
    Corporation. The company was first formally incorporated in 1866. The company
    continues to see both the United Kingdom and Hong Kong as its home markets.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/HSBC-Logo.png
  humanURL: https://hsbc.com
  baseURL: https://api.hsbc.com/open-banking/v2.1/
  tags: Current
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/hsbc/openapi.md
x-common:
- type: x-crunchbase
  url: https://crunchbase.com/organization/hsbc
- type: x-twitter
  url: https://twitter.com/HSBC
- type: x-developer
  url: https://developer.hsbc.com
- type: x-website
  url: https://hsbc.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---