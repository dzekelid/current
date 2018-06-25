---
name: Barclays
x-slug: barclays
description: 'Barclays is a British multinational bank and financial services company
  headquartered in London. It is a universal bank with global reach, offering products
  and services across personal, corporate and investment banking, credit cards and
  wealth management. It has operations in over 40 countries and employs approximately
  120,000 people. Barclays is organised into four core businesses: Personal &amp;
  Corporate (Personal Banking, Corporate Banking, Wealth &amp; Investment Management),
  Barclaycard, Investment Banking and Africa.'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/barclays-logo.png
x-kinRank: "7"
x-alexaRank: "77947"
tags: Current
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/barclays/apis.md
specificationVersion: "0.14"
apis:
- name: Barclays Get Current Personal Accounts
  x-api-slug: barclays
  description: This endpoint can contain multiple brands owned by a particular banking
    group. Each brand can own multiple PCA products.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/barclays-logo.png
  humanURL: https://barclays.com
  baseURL: https://atlas.api.barclays/open-banking/v2.1//personal-current-accounts/
  tags: Personal, Current, Accounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/barclays/personalcurrentaccounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/barclays/personalcurrentaccounts-get-openapi.md
- name: Barclays Get Current Business Accounts
  x-api-slug: barclays
  description: This endpoint can contain multiple brands owned by a particular banking
    group. Each brand can own multiple BCA products.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/barclays-logo.png
  humanURL: https://barclays.com
  baseURL: https://atlas.api.barclays/open-banking/v2.1//business-current-accounts/
  tags: Business, Current, Accounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/barclays/businesscurrentaccounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/barclays/businesscurrentaccounts-get-openapi.md
- name: Barclays
  x-api-slug: barclays
  description: 'Barclays is a British multinational bank and financial services company
    headquartered in London. It is a universal bank with global reach, offering products
    and services across personal, corporate and investment banking, credit cards and
    wealth management. It has operations in over 40 countries and employs approximately
    120,000 people. Barclays is organised into four core businesses: Personal &amp;
    Corporate (Personal Banking, Corporate Banking, Wealth &amp; Investment Management),
    Barclaycard, Investment Banking and Africa.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/barclays-logo.png
  humanURL: https://barclays.com
  baseURL: https://atlas.api.barclays/open-banking/v2.1/
  tags: Current
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/barclays/openapi.md
x-common:
- type: x-authentication
  url: https://developer.barclays.com/documentation/36324e85-05dc-4ffd-9301-0d0cf161e382.bdn/api#authentication
- type: x-code
  url: https://developer.barclays.com/catalogue/sdk
- type: x-crunchbase
  url: https://crunchbase.com/organization/barclays-plc
- type: x-developer
  url: https://developer.barclays.com/
- type: x-documentation
  url: https://developer.barclays.com/catalogue/api
- type: x-documentation
  url: https://developer.barclays.com/documentation/36324e85-05dc-4ffd-9301-0d0cf161e382.bdn/api
- type: x-privacy-policy
  url: https://developer.barclays.com/bdn/#/home/landing/Barclays_Developer_Privacy_Policy.htm
- type: x-selfservice-registration
  url: https://developer.barclays.com/bdn/#/home/signup
- type: x-terms-of-service
  url: https://developer.barclays.com/bdn/#/home/landing/Barclays_Developer_Agreement.htm
- type: x-twitter
  url: https://twitter.com/Barclays
- type: x-website
  url: https://barclays.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---