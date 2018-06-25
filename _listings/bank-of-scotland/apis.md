---
name: Bank of Scotland
x-slug: bank-of-scotland
description: The Bank of Scotland is a commercial and clearing bank based in Edinburgh,
  Scotland. With a history dating to the 17th century, it is the fifth-oldest surviving
  bank in the United Kingdom (the Bank of England having been established one year
  before), and is the only commercial institution created by the Parliament of Scotland
  to remain in existence. It was one of the first banks in Europe to print its own
  banknotes and it continues to print its own sterling banknotes under legal arrangements
  which allow Scottish banks to issue currency.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bank-of-scotland-logo.jpg
x-kinRank: "8"
x-alexaRank: "0"
tags: Current
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/bank-of-scotland/apis.md
specificationVersion: "0.14"
apis:
- name: Bank of Scotland Get Current Personal Accounts
  x-api-slug: bank-of-scotland
  description: This endpoint can contain multiple brands owned by a particular banking
    group. Each brand can own multiple PCA products.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bank-of-scotland-logo.jpg
  humanURL: https://www.bankofscotland.co.uk/
  baseURL: https://api.bankofscotland.co.uk/open-banking/v2.1//personal-current-accounts/
  tags: Personal, Current, Accounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/bank-of-scotland/personalcurrentaccounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/bank-of-scotland/personalcurrentaccounts-get-openapi.md
- name: Bank of Scotland Get Current Business Accounts
  x-api-slug: bank-of-scotland
  description: This endpoint can contain multiple brands owned by a particular banking
    group. Each brand can own multiple BCA products.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bank-of-scotland-logo.jpg
  humanURL: https://www.bankofscotland.co.uk/
  baseURL: https://api.bankofscotland.co.uk/open-banking/v2.1//business-current-accounts/
  tags: Business, Current, Accounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/bank-of-scotland/businesscurrentaccounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/bank-of-scotland/businesscurrentaccounts-get-openapi.md
- name: Bank of Scotland
  x-api-slug: bank-of-scotland
  description: The Bank of Scotland is a commercial and clearing bank based in Edinburgh,
    Scotland. With a history dating to the 17th century, it is the fifth-oldest surviving
    bank in the United Kingdom (the Bank of England having been established one year
    before), and is the only commercial institution created by the Parliament of Scotland
    to remain in existence. It was one of the first banks in Europe to print its own
    banknotes and it continues to print its own sterling banknotes under legal arrangements
    which allow Scottish banks to issue currency.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bank-of-scotland-logo.jpg
  humanURL: https://www.bankofscotland.co.uk/
  baseURL: https://api.bankofscotland.co.uk/open-banking/v2.1/
  tags: Current
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/bank-of-scotland/openapi.md
x-common:
- type: x-twitter
  url: https://twitter.com/AskBankOfScot
- type: x-website
  url: https://www.bankofscotland.co.uk/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---