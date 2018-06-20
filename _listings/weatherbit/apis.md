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
tags: Hourly
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/apis.md
specificationVersion: "0.14"
apis:
- name: Weatherbit Get Bulk History Hourly City & Country
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a city in the format of City,ST
    or City. The state, and country parameters can be provided to make the search
    more accurate.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//bulk/history/hourly?city={city}&country={country}
  tags: Weather,Bulk, History, Hourly, City, City, &country, Country
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/bulkhistoryhourlycitycitycountrycountry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/bulkhistoryhourlycitycitycountrycountry-get-openapi.md
- name: Weatherbit Get Bulk History Hourly City
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a City ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//bulk/history/hourly?city_id={city_id}
  tags: Weather,Bulk, History, Hourly, City, , City
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/bulkhistoryhourlycity-idcity-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/bulkhistoryhourlycity-idcity-id-get-openapi.md
- name: Weatherbit Get Bulk History Hourly IP
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given IP Address, or auto.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//bulk/history/hourly?ip={ip}
  tags: Weather,Bulk, History, Hourly, Ip, Ip
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/bulkhistoryhourlyipip-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/bulkhistoryhourlyipip-get-openapi.md
- name: Weatherbit Get Bulk History Hourly Lat & Lon
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a lat, and lon.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//bulk/history/hourly?lat={lat}&lon={lon}
  tags: Weather,Bulk, History, Hourly, Lat, Lat, &lon, Lon
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/bulkhistoryhourlylatlatlonlon-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/bulkhistoryhourlylatlatlonlon-get-openapi.md
- name: Weatherbit Get Bulk History Hourly Postal Code
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a Postal Code.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//bulk/history/hourly?postal_code={postal_code}
  tags: Weather,Bulk, History, Hourly, Postal, Code, Postal, Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/bulkhistoryhourlypostal-codepostal-code-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/bulkhistoryhourlypostal-codepostal-code-get-openapi.md
- name: Weatherbit Get Bulk History Hourly Station
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a station ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//bulk/history/hourly?station={station}
  tags: Weather,Bulk, History, Hourly, Station, Station
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/bulkhistoryhourlystationstation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/bulkhistoryhourlystationstation-get-openapi.md
- name: Weatherbit Get Forecast 3hourly City & Country
  x-api-slug: weatherbit
  description: Returns a 3-hourly forecast, where each point represents a three hour   period.
    Every point has a datetime string in the format "YYYY-MM-DD:HH". Time is UTC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/3hourly?city={city}&country={country}
  tags: Weather,Forecast, 3hourly, City, City, &country, Country
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/forecast3hourlycitycitycountrycountry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/forecast3hourlycitycitycountrycountry-get-openapi.md
- name: Weatherbit Get Forecast 3hourly City
  x-api-slug: weatherbit
  description: Returns a 3-hourly forecast, where each point represents a three hour   period.
    Every point has a datetime string in the format "YYYY-MM-DD:HH". Time is UTC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/3hourly?city_id={city_id}
  tags: Weather,Forecast, 3hourly, City, , City
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/forecast3hourlycity-idcity-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/forecast3hourlycity-idcity-id-get-openapi.md
- name: Weatherbit Get Forecast 3hourly IP
  x-api-slug: weatherbit
  description: Returns a 3-hourly forecast, where each point represents a three hour   period.
    Every point has a datetime string in the format "YYYY-MM-DD:HH". Time is UTC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/3hourly?ip={ip}
  tags: Weather,Forecast, 3hourly, Ip, Ip
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/forecast3hourlyipip-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/forecast3hourlyipip-get-openapi.md
- name: Weatherbit Get Forecast 3hourly Lat & Lon
  x-api-slug: weatherbit
  description: Returns a 3-hourly forecast, where each point represents a three hour   period.
    Every point has a datetime string in the format "YYYY-MM-DD:HH". Time is UTC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/3hourly?lat={lat}&lon={lon}
  tags: Weather,Forecast, 3hourly, Lat, Lat, &lon, Lon
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/forecast3hourlylatlatlonlon-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/forecast3hourlylatlatlonlon-get-openapi.md
- name: Weatherbit Get Forecast 3hourly Postla Code Code
  x-api-slug: weatherbit
  description: Returns a 3-hourly forecast, where each point represents a three hour
    period. Every point has a datetime string in the format "YYYY-MM-DD:HH". Time
    is UTC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/3hourly?postal_code={postal_code}
  tags: Weather,Forecast, 3hourly, Postal, Code, Postal, Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/forecast3hourlypostal-codepostal-code-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/forecast3hourlypostal-codepostal-code-get-openapi.md
- name: Weatherbit Get Forecast Hourly City & Country
  x-api-slug: weatherbit
  description: '**(REQUIRED: Developer Plan or Higher)** Returns an hourly forecast,
    where each point represents a one hour   period. Every point has a datetime string
    in the format "YYYY-MM-DD:HH". Time is UTC. Accepts a city in the format of City,ST
    or City. The state, and country parameters can be provided to make the search
    more accurate.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/hourly?city={city}&country={country}
  tags: Weather,Forecast, Hourly, City, City, &country, Country
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/forecasthourlycitycitycountrycountry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/forecasthourlycitycitycountrycountry-get-openapi.md
- name: Weatherbit Get Forecast Hourly City
  x-api-slug: weatherbit
  description: '**(REQUIRED: Developer Plan or Higher)** Returns an hourly forecast,
    where each point represents a one hour   period. Every point has a datetime string
    in the format "YYYY-MM-DD:HH". Time is UTC.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/hourly?city_id={city_id}
  tags: Weather,Forecast, Hourly, City, , City
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/forecasthourlycity-idcity-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/forecasthourlycity-idcity-id-get-openapi.md
- name: Weatherbit Get Forecast Hourly IP
  x-api-slug: weatherbit
  description: '**(REQUIRED: Developer Plan or Higher)** Returns an hourly forecast,
    where each point represents a one hour period. Every point has a datetime string
    in the format "YYYY-MM-DD:HH". Time is UTC.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/hourly?ip={ip}
  tags: Weather,Forecast, Hourly, Ip, Ip
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/forecasthourlyipip-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/forecasthourlyipip-get-openapi.md
- name: Weatherbit Get Forecast Hourly Lat & Lon
  x-api-slug: weatherbit
  description: '**(REQUIRED: Developer Plan or Higher)** Returns an hourly forecast,
    where each point represents a one hour period. Every point has a datetime string
    in the format "YYYY-MM-DD:HH". Time is UTC.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/hourly?lat={lat}&lon={lon}
  tags: Weather,Forecast, Hourly, Lat, Lat, &lon, Lon
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/forecasthourlylatlatlonlon-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/forecasthourlylatlatlonlon-get-openapi.md
- name: Weatherbit Get Forecast Hourly Postla Code Code
  x-api-slug: weatherbit
  description: '**(REQUIRED: Developer Plan or Higher)** Returns an hourly forecast,
    where each point represents a one hour   period. Every point has a datetime string
    in the format "YYYY-MM-DD:HH". Time is UTC.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/hourly?postal_code={postal_code}
  tags: Weather,Forecast, Hourly, Postal, Code, Postal, Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/forecasthourlypostal-codepostal-code-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/forecasthourlypostal-codepostal-code-get-openapi.md
- name: Weatherbit Get History Hourly City & Country
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a city in the format of City,ST
    or City. The state, and country parameters can be provided to make the search
    more accurate. **(LIMIT 1 day for Low Volume plans. LIMIT 7 days for Basic/Developer.
    LIMIT 30 days for Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/hourly?city={city}&country={country}
  tags: Weather,History, Hourly, City, City, &country, Country
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/historyhourlycitycitycountrycountry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/historyhourlycitycitycountrycountry-get-openapi.md
- name: Weatherbit Get History Hourly City
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a City ID. **(LIMIT 1 day for
    Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/hourly?city_id={city_id}
  tags: Weather,History, Hourly, City, , City
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/historyhourlycity-idcity-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/historyhourlycity-idcity-id-get-openapi.md
- name: Weatherbit Get History Hourly IP
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given IP Address, or auto. **(LIMIT
    1 day for Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for
    Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/hourly?ip={ip}
  tags: Weather,History, Hourly, Ip, Ip
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/historyhourlyipip-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/historyhourlyipip-get-openapi.md
- name: Weatherbit Get History Hourly Lat & Lon
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a lat, and lon. **(LIMIT 1
    day for Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for
    Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/hourly?lat={lat}&lon={lon}
  tags: Weather,History, Hourly, Lat, Lat, &lon, Lon
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/historyhourlylatlatlonlon-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/historyhourlylatlatlonlon-get-openapi.md
- name: Weatherbit Get History Hourly Postal Code
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a Postal Code. **(LIMIT 1 day
    for Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/hourly?postal_code={postal_code}
  tags: Weather,History, Hourly, Postal, Code, Postal, Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/historyhourlypostal-codepostal-code-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/historyhourlypostal-codepostal-code-get-openapi.md
- name: Weatherbit Get History Hourly Station Station
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a station ID. **(LIMIT 1 day
    for Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/hourly?station={station}
  tags: Weather,History, Hourly, Station, Station
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/historyhourlystationstation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/historyhourlystationstation-get-openapi.md
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
  tags: Hourly
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hourly/master/_listings/weatherbit/openapi.md
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