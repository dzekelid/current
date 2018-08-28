swagger: "2.0"
x-collection-name: nFusion Solutions
x-complete: 1
info:
  title: nFusion Solutions Market Data API v1
  description: nfusion-solutions-provides-rest-and-streaming-apis-that-deliver-enterprisegrade-financial-data--data-sets-include-realtime-and-historical-pricing-for-spot-prices-of-precious-metals-such-as-gold-silver-platinum-and-palladium-exchange-rates-for-major-currency-pairs-exchange-rates-for-crypto-currencies-such-as-btc-eth-and-ltc--all-api-access-requires-authentication--in-order-to-be-issued-access-credentials-you-must-first-enter-into-a-service-agreement-with-nfusion-solutions-and-acquire-a-commercial-license--for-information-on-how-to-obtain-a-licence-contact-salesnfusionsolutions-com-
  contact:
    name: nFusion Solutions
    url: https://nfusionsolutions.com/contact
    email: support@nfusionsolutions.com
  version: 1.0.0
host: api.nfusionsolutions.biz
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v{version}/Currencies/summary:
    get:
      summary: Get latest Summary for requested currency pairs
      description: Current and daily summary information combined into a single quote
      operationId: ApiV{versionCurrenciesSummaryGet
      x-api-path-slug: apivversioncurrenciessummary-get
      parameters:
      - in: query
        name: format
        description: to override content negotiation specify a value of json or xml
      - in: query
        name: pairs
        description: comma separated list of currency pairs
      - in: query
        name: token
        description: auth token
      - in: path
        name: version
        description: The requested API version
      responses:
        200:
          description: OK
      tags:
      - Latest
      - Summaryrequested
      - Currency
      - Pairs
  /api/v{version}/Metals/spot/summary:
    get:
      summary: Get latest Spot Summary for requested metals
      description: Current and daily summary information combined into a single quote
      operationId: ApiV{versionMetalsSpotSummaryGet
      x-api-path-slug: apivversionmetalsspotsummary-get
      parameters:
      - in: query
        name: adjust
        description: apply global and per-tenant spot price adjustments
      - in: query
        name: currency
        description: comma separated list of conversion currencies, defaults to USD
      - in: query
        name: format
        description: to override content negotiation specify a value of json or xml
      - in: query
        name: metals
        description: comma separated list of metals
      - in: query
        name: token
        description: auth token
      - in: query
        name: unitofmeasure
        description: unit of meaure, defaults to troy ounces
      - in: path
        name: version
        description: The requested API version
      responses:
        200:
          description: OK
      tags:
      - Latest
      - Spot
      - Summaryrequested
      - Metals