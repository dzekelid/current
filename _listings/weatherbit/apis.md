---
name: Weatherbit
x-slug: weatherbit
description: Our mission at Weatherbit.io is pretty simple. It is to provide the highest
  quality weather forecasts, observations, and historical weather data at the best
  price. We constantly improve our platform every day. Our Weather APIs grow with
  you. Have a feature request? Let us know on our Support Forum! Our commitment to
  data quality is unparalleled. Our forecast system uses global forecast models (GFS/ECMWF),
  in combination with local short range high resolution models to derive the most
  accurate, and relevant forecast apis on the web.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Current
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/weatherbit/apis.md
specificationVersion: "0.14"
apis:
- name: Weatherbit Get Current Cities
  x-api-slug: weatherbit
  description: '**(Advanced/Advanced+/Enterprise plans only)** Returns a group of
    Current Observations - Given a list of City IDs.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//current?city={city}
  tags: Weather,Current, Cities, Cities
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/weatherbit/currentcitycity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/weatherbit/currentcitycity-get-openapi.md
- name: Weatherbit Get Current IP
  x-api-slug: weatherbit
  description: Returns a Current Observation - Given an IP address, or auto.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//current?ip={ip}
  tags: Weather,Current, Ip, Ip
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/weatherbit/currentipip-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/weatherbit/currentipip-get-openapi.md
- name: Weatherbit Get Current Lat & Lon
  x-api-slug: weatherbit
  description: Returns a Current Observation - given a lat, and a lon.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//current?lat={lat}&lon={lon}
  tags: Weather,Current, Lat, Lat, &lon, Lon
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/weatherbit/currentlatlatlonlon-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/weatherbit/currentlatlatlonlon-get-openapi.md
- name: Weatherbit Get Current Postla Code Code
  x-api-slug: weatherbit
  description: Returns current weather observation - Given a Postal Code.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//current?postal_code={postal_code}
  tags: Weather,Current, Postal, Code, Postal, Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/weatherbit/currentpostal-codepostal-code-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/weatherbit/currentpostal-codepostal-code-get-openapi.md
- name: Weatherbit Get Current Station Station
  x-api-slug: weatherbit
  description: Returns a Current Observation - Given a station ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//current?station={station}
  tags: Weather,Current, Station, Station
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/weatherbit/currentstationstation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/weatherbit/currentstationstation-get-openapi.md
- name: Weatherbit Get Current Stations Stations
  x-api-slug: weatherbit
  description: '**(Advanced/Advanced+/Enterprise plans only)** Returns a group of
    Current Observations - Given a list of Station Call IDs.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//current?stations={stations}
  tags: Weather,Current, Stations, Stations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/weatherbit/currentstationsstations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/weatherbit/currentstationsstations-get-openapi.md
- name: Weatherbit
  x-api-slug: weatherbit
  description: Our mission at Weatherbit.io is pretty simple. It is to provide the
    highest quality weather forecasts, observations, and historical weather data at
    the best price. We constantly improve our platform every day. Our Weather APIs
    grow with you. Have a feature request? Let us know on our Support Forum! Our commitment
    to data quality is unparalleled. Our forecast system uses global forecast models
    (GFS/ECMWF), in combination with local short range high resolution models to derive
    the most accurate, and relevant forecast apis on the web.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0
  tags: Current
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/current/master/_listings/weatherbit/openapi.md
x-common:
- type: x-blog
  url: https://www.weatherbit.io/blog
- type: x-contact-form
  url: https://www.weatherbit.io/contact
- type: x-documentation
  url: https://www.weatherbit.io/api
- type: x-github
  url: https://github.com/weatherbit
- type: x-pricing
  url: https://www.weatherbit.io/pricing
- type: x-twitter
  url: https://twitter.com/weatherbitio
- type: x-website
  url: http://weatherbit.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---