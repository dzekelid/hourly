---
swagger: "2.0"
x-collection-name: ClimaCell
x-complete: 1
info:
  title: ClimaCell API
  description: the-climacell-rest-api-provides-access-to-high-resolution-weather-data-for-locations-across-the-u-s--with-global-data-coming-soon--it-uses-https-and-requires-an-access-token-key--the-api-requests-carry-query-parameters-and-the-responses-return-results-in-json-format-
  version: 1.0.0
host: api2.climacell.co
basePath: /v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /hourly:
    post:
      summary: Post Hourly
      description: "## Hourly Forecast Weather Data (Coming Soon)\nThe ```\u200Bhourly\u200B```
        API call provides an hourly forecast, up to 120 hours (5 days) ahead as a
        time series, for a specific location based on ClimaCell\u2019s proprietary
        sensing technology and model. The location can be specified as a geocode,
        or one of your own defined locations (see locations API calls). The weather
        parameters returned are detailed in the \u200B__Weather Data\u200B__ section."
      operationId: -hourly-forecast-weather-data-coming-soonthe-hourly-api-call-provides-an-hourly-forecast-up-to-120-h
      x-api-path-slug: hourly-post
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Hourly
---