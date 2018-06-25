---
name: Weatherbit.io
x-slug: weatherbit-io
description: Our Weather API is the most powerful Weather data API on the web. Sign
  up for our free Weather API, and upgrade as your weather data needs grow!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
x-kinRank: "8"
x-alexaRank: "1016253"
tags: Hourly
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/apis.md
specificationVersion: "0.14"
apis:
- name: Weatherbit Get Bulk History Hourly City & Country
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a city in the format of City,ST
    or City. The state, and country parameters can be provided to make the search
    more accurate.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//bulk/history/hourly?city={city}&country={country}
  tags: Weather,Bulk, History, Hourly, City, City, &country, Country
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/bulkhistoryhourlycitycitycountrycountry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/bulkhistoryhourlycitycitycountrycountry-get-openapi.md
- name: Weatherbit Get Bulk History Hourly City
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a City ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//bulk/history/hourly?city_id={city_id}
  tags: Weather,Bulk, History, Hourly, City, , City
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/bulkhistoryhourlycity-idcity-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/bulkhistoryhourlycity-idcity-id-get-openapi.md
- name: Weatherbit Get Bulk History Hourly IP
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given IP Address, or auto.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//bulk/history/hourly?ip={ip}
  tags: Weather,Bulk, History, Hourly, Ip, Ip
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/bulkhistoryhourlyipip-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/bulkhistoryhourlyipip-get-openapi.md
- name: Weatherbit Get Bulk History Hourly Lat & Lon
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a lat, and lon.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//bulk/history/hourly?lat={lat}&lon={lon}
  tags: Weather,Bulk, History, Hourly, Lat, Lat, &lon, Lon
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/bulkhistoryhourlylatlatlonlon-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/bulkhistoryhourlylatlatlonlon-get-openapi.md
- name: Weatherbit Get Bulk History Hourly Postal Code
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a Postal Code.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//bulk/history/hourly?postal_code={postal_code}
  tags: Weather,Bulk, History, Hourly, Postal, Code, Postal, Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/bulkhistoryhourlypostal-codepostal-code-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/bulkhistoryhourlypostal-codepostal-code-get-openapi.md
- name: Weatherbit Get Bulk History Hourly Station
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a station ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//bulk/history/hourly?station={station}
  tags: Weather,Bulk, History, Hourly, Station, Station
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/bulkhistoryhourlystationstation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/bulkhistoryhourlystationstation-get-openapi.md
- name: Weatherbit Get Forecast 3hourly City & Country
  x-api-slug: weatherbit
  description: Returns a 3-hourly forecast, where each point represents a three hour   period.
    Every point has a datetime string in the format "YYYY-MM-DD:HH". Time is UTC.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/3hourly?city={city}&country={country}
  tags: Weather,Forecast, 3hourly, City, City, &country, Country
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/forecast3hourlycitycitycountrycountry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/forecast3hourlycitycitycountrycountry-get-openapi.md
- name: Weatherbit Get Forecast 3hourly City
  x-api-slug: weatherbit
  description: Returns a 3-hourly forecast, where each point represents a three hour   period.
    Every point has a datetime string in the format "YYYY-MM-DD:HH". Time is UTC.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/3hourly?city_id={city_id}
  tags: Weather,Forecast, 3hourly, City, , City
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/forecast3hourlycity-idcity-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/forecast3hourlycity-idcity-id-get-openapi.md
- name: Weatherbit Get Forecast 3hourly IP
  x-api-slug: weatherbit
  description: Returns a 3-hourly forecast, where each point represents a three hour   period.
    Every point has a datetime string in the format "YYYY-MM-DD:HH". Time is UTC.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/3hourly?ip={ip}
  tags: Weather,Forecast, 3hourly, Ip, Ip
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/forecast3hourlyipip-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/forecast3hourlyipip-get-openapi.md
- name: Weatherbit Get Forecast 3hourly Lat & Lon
  x-api-slug: weatherbit
  description: Returns a 3-hourly forecast, where each point represents a three hour   period.
    Every point has a datetime string in the format "YYYY-MM-DD:HH". Time is UTC.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/3hourly?lat={lat}&lon={lon}
  tags: Weather,Forecast, 3hourly, Lat, Lat, &lon, Lon
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/forecast3hourlylatlatlonlon-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/forecast3hourlylatlatlonlon-get-openapi.md
- name: Weatherbit Get Forecast 3hourly Postla Code Code
  x-api-slug: weatherbit
  description: Returns a 3-hourly forecast, where each point represents a three hour
    period. Every point has a datetime string in the format "YYYY-MM-DD:HH". Time
    is UTC.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/3hourly?postal_code={postal_code}
  tags: Weather,Forecast, 3hourly, Postal, Code, Postal, Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/forecast3hourlypostal-codepostal-code-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/forecast3hourlypostal-codepostal-code-get-openapi.md
- name: Weatherbit Get Forecast Hourly City & Country
  x-api-slug: weatherbit
  description: '**(REQUIRED: Developer Plan or Higher)** Returns an hourly forecast,
    where each point represents a one hour   period. Every point has a datetime string
    in the format "YYYY-MM-DD:HH". Time is UTC. Accepts a city in the format of City,ST
    or City. The state, and country parameters can be provided to make the search
    more accurate.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/hourly?city={city}&country={country}
  tags: Weather,Forecast, Hourly, City, City, &country, Country
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/forecasthourlycitycitycountrycountry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/forecasthourlycitycitycountrycountry-get-openapi.md
- name: Weatherbit Get Forecast Hourly City
  x-api-slug: weatherbit
  description: '**(REQUIRED: Developer Plan or Higher)** Returns an hourly forecast,
    where each point represents a one hour   period. Every point has a datetime string
    in the format "YYYY-MM-DD:HH". Time is UTC.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/hourly?city_id={city_id}
  tags: Weather,Forecast, Hourly, City, , City
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/forecasthourlycity-idcity-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/forecasthourlycity-idcity-id-get-openapi.md
- name: Weatherbit Get Forecast Hourly IP
  x-api-slug: weatherbit
  description: '**(REQUIRED: Developer Plan or Higher)** Returns an hourly forecast,
    where each point represents a one hour period. Every point has a datetime string
    in the format "YYYY-MM-DD:HH". Time is UTC.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/hourly?ip={ip}
  tags: Weather,Forecast, Hourly, Ip, Ip
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/forecasthourlyipip-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/forecasthourlyipip-get-openapi.md
- name: Weatherbit Get Forecast Hourly Lat & Lon
  x-api-slug: weatherbit
  description: '**(REQUIRED: Developer Plan or Higher)** Returns an hourly forecast,
    where each point represents a one hour period. Every point has a datetime string
    in the format "YYYY-MM-DD:HH". Time is UTC.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/hourly?lat={lat}&lon={lon}
  tags: Weather,Forecast, Hourly, Lat, Lat, &lon, Lon
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/forecasthourlylatlatlonlon-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/forecasthourlylatlatlonlon-get-openapi.md
- name: Weatherbit Get Forecast Hourly Postla Code Code
  x-api-slug: weatherbit
  description: '**(REQUIRED: Developer Plan or Higher)** Returns an hourly forecast,
    where each point represents a one hour   period. Every point has a datetime string
    in the format "YYYY-MM-DD:HH". Time is UTC.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/hourly?postal_code={postal_code}
  tags: Weather,Forecast, Hourly, Postal, Code, Postal, Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/forecasthourlypostal-codepostal-code-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/forecasthourlypostal-codepostal-code-get-openapi.md
- name: Weatherbit Get History Hourly City & Country
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a city in the format of City,ST
    or City. The state, and country parameters can be provided to make the search
    more accurate. **(LIMIT 1 day for Low Volume plans. LIMIT 7 days for Basic/Developer.
    LIMIT 30 days for Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/hourly?city={city}&country={country}
  tags: Weather,History, Hourly, City, City, &country, Country
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/historyhourlycitycitycountrycountry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/historyhourlycitycitycountrycountry-get-openapi.md
- name: Weatherbit Get History Hourly City
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a City ID. **(LIMIT 1 day for
    Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/hourly?city_id={city_id}
  tags: Weather,History, Hourly, City, , City
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/historyhourlycity-idcity-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/historyhourlycity-idcity-id-get-openapi.md
- name: Weatherbit Get History Hourly IP
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given IP Address, or auto. **(LIMIT
    1 day for Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for
    Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/hourly?ip={ip}
  tags: Weather,History, Hourly, Ip, Ip
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/historyhourlyipip-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/historyhourlyipip-get-openapi.md
- name: Weatherbit Get History Hourly Lat & Lon
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a lat, and lon. **(LIMIT 1
    day for Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for
    Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/hourly?lat={lat}&lon={lon}
  tags: Weather,History, Hourly, Lat, Lat, &lon, Lon
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/historyhourlylatlatlonlon-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/historyhourlylatlatlonlon-get-openapi.md
- name: Weatherbit Get History Hourly Postal Code
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a Postal Code. **(LIMIT 1 day
    for Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/hourly?postal_code={postal_code}
  tags: Weather,History, Hourly, Postal, Code, Postal, Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/historyhourlypostal-codepostal-code-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/historyhourlypostal-codepostal-code-get-openapi.md
- name: Weatherbit Get History Hourly Station Station
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a station ID. **(LIMIT 1 day
    for Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/hourly?station={station}
  tags: Weather,History, Hourly, Station, Station
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/historyhourlystationstation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/historyhourlystationstation-get-openapi.md
- name: Weatherbit
  x-api-slug: weatherbit
  description: Our Weather API is the most powerful Weather data API on the web. Sign
    up for our free Weather API, and upgrade as your weather data needs grow!
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0
  tags: Hourly
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit-io/openapi.md
x-common:
- type: x-blog
  url: https://www.weatherbit.io/blog
- type: x-contact-form
  url: https://www.weatherbit.io/contact
- type: x-crunchbase
  url: https://crunchbase.com/organization/product/weather-it-
- type: x-documentation
  url: https://www.weatherbit.io/api
- type: x-email
  url: support@weatherbit.io
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