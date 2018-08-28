swagger: "2.0"
x-collection-name: Lykke
x-complete: 1
info:
  title: Wallet_Api
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/Ethereum/getCurrentNetworkGas:
    get:
      summary: Get API Ethereum Getcurrentnetworkgas
      description: Get api ethereum getcurrentnetworkgas.
      operationId: ApiEthereumGetCurrentNetworkGasGet
      x-api-path-slug: apiethereumgetcurrentnetworkgas-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Ethereum
      - Currentnetworkgas