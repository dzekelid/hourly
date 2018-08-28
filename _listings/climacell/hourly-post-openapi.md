---
swagger: "2.0"
x-collection-name: ClimaCell
x-complete: 0
info:
  title: ClimaCell Post Hourly
  description: |-
    ## Hourly Forecast Weather Data (Coming Soon)
    The ```???hourly???``` API call provides an hourly forecast, up to 120 hours (5 days) ahead as a time series, for a specific location based on ClimaCell???s proprietary sensing technology and model. The location can be specified as a geocode, or one of your own defined locations (see locations API calls). The weather parameters returned are detailed in the ???__Weather Data???__ section.
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
      description: |-
        ## Hourly Forecast Weather Data (Coming Soon)
        The ```???hourly???``` API call provides an hourly forecast, up to 120 hours (5 days) ahead as a time series, for a specific location based on ClimaCell???s proprietary sensing technology and model. The location can be specified as a geocode, or one of your own defined locations (see locations API calls). The weather parameters returned are detailed in the ???__Weather Data???__ section.
      operationId: -hourly-forecast-weather-data-coming-soonthe-hourly-api-call-provides-an-hourly-forecast-up-to-120-h
      x-api-path-slug: hourly-post
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Hourly
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---