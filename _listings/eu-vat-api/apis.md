---
name: EU VAT API
x-slug: eu-vat-api
description: A developer friendly API to help your business achieve VAT compliance.
  Are you selling digital services to other EU countries? From Jan 1st 2015 changes
  to the VAT place of supply are coming into effect. One acceptable way to prove where
  your customer resides is their IP address. We have removed the headache and cost
  of you having to geo locate your customers IP address, and workout what VAT rate
  they should be charged. Simply pass your customers IP address from your application
  to our API and well return a JSON or XML object of all the current EU VAT rates
  for that country, or if you already know their country you can lookup the rates
  from the 2 digit country code.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/vatapi-logo.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Current
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/eu-vat-api/apis.md
specificationVersion: "0.14"
apis:
- name: VAT API - Check api requests remaining on current subscription plan
  x-api-slug: usagecheck-get
  description: Check api requests remaining on current subscription plan.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/vatapi-logo.png
  humanURL: http://vatapi.com
  baseURL: https://vatapi.com//v1
  tags: VAT, EU, Taxes, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/eu-vat-api/usagecheck-get-openapi.md
- name: VAT API - Retrieve all current EU VAT rates
  x-api-slug: vatrates-get
  description: Retrieve all current eu vat rates.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/vatapi-logo.png
  humanURL: http://vatapi.com
  baseURL: https://vatapi.com//v1
  tags: VAT, EU, Taxes, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/eu-vat-api/vatrates-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://eu.bon.utis.api.gallery.streamdata.io
- type: x-api-stack
  url: http://eu.vat.api.stack.network
- type: x-website
  url: http://vatapi.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---