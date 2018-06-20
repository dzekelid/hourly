---
swagger: "2.0"
x-collection-name: Weather Underground
x-complete: 1
info:
  title: Weather Underground
  description: get-forecast-and-weather-data-with-complete-geolocation-services-global-coverage-and-more-
  version: 1.0.0
host: api.wunderground.com
basePath: /api/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{key}/hourly/q/CA/San_Francisco.json:
    get:
      summary: Get Key Hourly Q Ca San Francisco
      description: This example will return a detailed hourly forecast for the 'next'
        36 hours in San Francisco, California
      operationId: Get_OneDay_hourly_example_
      x-api-path-slug: keyhourlyqcasan-francisco-json-get
      parameters:
      - in: path
        name: city
        description: The city
        type: string
        format: string
      - in: path
        name: state
        description: The state
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Key
      - Hourly
      - Q
      - CA
      - San
      - Francisco
      - Json
  /{key}/hourly10day/q/CA/San_Francisco.json:
    get:
      summary: Get Key Hourly10day Q Ca San Francisco
      description: This example will return a detailed hourly forecast for the next
        10 days in San Francisco, California
      operationId: Get_TenDay_hourly_example_
      x-api-path-slug: keyhourly10dayqcasan-francisco-json-get
      parameters:
      - in: path
        name: city
        description: The city
        type: string
        format: string
      - in: path
        name: state
        description: The state
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Key
      - Hourly10day
      - Q
      - CA
      - San
      - Francisco
      - Json
---