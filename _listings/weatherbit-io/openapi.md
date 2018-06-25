---
swagger: "2.0"
x-collection-name: Weatherbit.io
x-complete: 1
info:
  title: Weatherbit
  description: this-is-the-documentation-for-the-weatherbit-api---the-base-url-for-the-api-is-httpapi-weatherbit-iov2-0httpapi-weatherbit-iov2-0-or-httpsapi-weatherbit-iov2-0httpapi-weatherbit-iov2-0--below-is-the-swagger-ui-documentation-for-the-api--all-api-requests-require-the-key-parameter---------an-example-for-a-5-day-forecast-for-london-uk-would-be-httpapi-weatherbit-iov2-0forecast3hourlycitylondoncountryuk
  version: 2.0.0
host: api.weatherbit.io
basePath: /v2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /bulk/history/hourly?city={city}&country={country}:
    get:
      summary: Get Bulk History Hourly City & Country
      description: Returns Historical Observations - Given a city in the format of
        City,ST or City. The state, and country parameters can be provided to make
        the search more accurate.
      operationId: returns-historical-observations--given-a-city-in-the-format-of-cityst-or-city-the-state-and-country-
      x-api-path-slug: bulkhistoryhourlycitycitycountrycountry-get
      parameters:
      - in: query
        name: callback
        description: Wraps return in jsonp callback
      - in: path
        name: city
        description: City search
      - in: path
        name: country
        description: Country Code (2 letter)
      - in: query
        name: end_date
        description: End Date (YYYY-MM-DD or YYYY-MM-DD:HH)
      - in: query
        name: key
        description: Your registered API key
      - in: query
        name: lang
        description: 'Language (Default: English) See language field description'
      - in: query
        name: start_date
        description: Start Date (YYYY-MM-DD or YYYY-MM-DD:HH)
      - in: query
        name: state
        description: Full name of state
      - in: query
        name: units
        description: Convert to units
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Bulk
      - History
      - Hourly
      - City
      - City
      - '&country'
      - Country
  /bulk/history/hourly?city_id={city_id}:
    get:
      summary: Get Bulk History Hourly City
      description: Returns Historical Observations - Given a City ID.
      operationId: returns-historical-observations--given-a-city-id
      x-api-path-slug: bulkhistoryhourlycity-idcity-id-get
      parameters:
      - in: query
        name: callback
        description: Wraps return in jsonp callback
      - in: path
        name: city_id
        description: City ID
      - in: query
        name: end_date
        description: End Date (YYYY-MM-DD or YYYY-MM-DD:HH)
      - in: query
        name: key
        description: Your registered API key
      - in: query
        name: lang
        description: 'Language (Default: English) See language field description'
      - in: query
        name: start_date
        description: Start Date (YYYY-MM-DD or YYYY-MM-DD:HH)
      - in: query
        name: units
        description: Convert to units
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Bulk
      - History
      - Hourly
      - City
      - ""
      - City
  /bulk/history/hourly?ip={ip}:
    get:
      summary: Get Bulk History Hourly IP
      description: Returns Historical Observations - Given IP Address, or auto.
      operationId: returns-historical-observations--given-ip-address-or-auto
      x-api-path-slug: bulkhistoryhourlyipip-get
      parameters:
      - in: query
        name: callback
        description: Wraps return in jsonp callback
      - in: query
        name: end_date
        description: End Date (YYYY-MM-DD or YYYY-MM-DD:HH)
      - in: path
        name: ip
        description: IP Address, or auto
      - in: query
        name: key
        description: Your registered API key
      - in: query
        name: lang
        description: 'Language (Default: English) See language field description'
      - in: query
        name: start_date
        description: Start Date (YYYY-MM-DD or YYYY-MM-DD:HH)
      - in: query
        name: units
        description: Convert to units
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Bulk
      - History
      - Hourly
      - Ip
      - Ip
  /bulk/history/hourly?lat={lat}&lon={lon}:
    get:
      summary: Get Bulk History Hourly Lat & Lon
      description: Returns Historical Observations - Given a lat, and lon.
      operationId: returns-historical-observations--given-a-lat-and-lon
      x-api-path-slug: bulkhistoryhourlylatlatlonlon-get
      parameters:
      - in: query
        name: callback
        description: Wraps return in jsonp callback
      - in: query
        name: end_date
        description: End Date (YYYY-MM-DD or YYYY-MM-DD:HH)
      - in: query
        name: key
        description: Your registered API key
      - in: query
        name: lang
        description: 'Language (Default: English) See language field description'
      - in: path
        name: lat
        description: Latitude component of location
      - in: path
        name: lon
        description: Longitude component of location
      - in: query
        name: start_date
        description: Start Date (YYYY-MM-DD or YYYY-MM-DD:HH)
      - in: query
        name: units
        description: Convert to units
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Bulk
      - History
      - Hourly
      - Lat
      - Lat
      - '&lon'
      - Lon
  /bulk/history/hourly?postal_code={postal_code}:
    get:
      summary: Get Bulk History Hourly Postal Code
      description: Returns Historical Observations - Given a Postal Code.
      operationId: returns-historical-observations--given-a-postal-code-
      x-api-path-slug: bulkhistoryhourlypostal-codepostal-code-get
      parameters:
      - in: query
        name: callback
        description: Wraps return in jsonp callback
      - in: query
        name: country
        description: Country Code (2 letter)
      - in: query
        name: end_date
        description: End Date (YYYY-MM-DD or YYYY-MM-DD:HH)
      - in: query
        name: key
        description: Your registered API key
      - in: query
        name: lang
        description: 'Language (Default: English) See language field description'
      - in: path
        name: postal_code
        description: Postal Code
      - in: query
        name: start_date
        description: Start Date (YYYY-MM-DD or YYYY-MM-DD:HH)
      - in: query
        name: units
        description: Convert to units
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Bulk
      - History
      - Hourly
      - Postal
      - Code
      - Postal
      - Code
  /bulk/history/hourly?station={station}:
    get:
      summary: Get Bulk History Hourly Station
      description: Returns Historical Observations - Given a station ID.
      operationId: returns-historical-observations--given-a-station-id
      x-api-path-slug: bulkhistoryhourlystationstation-get
      parameters:
      - in: query
        name: callback
        description: Wraps return in jsonp callback
      - in: query
        name: end_date
        description: End Date (YYYY-MM-DD or YYYY-MM-DD:HH)
      - in: query
        name: key
        description: Your registered API key
      - in: query
        name: lang
        description: 'Language (Default: English) See language field description'
      - in: query
        name: start_date
        description: Start Date (YYYY-MM-DD or YYYY-MM-DD:HH)
      - in: path
        name: station
        description: Station ID
      - in: query
        name: units
        description: Convert to units
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Bulk
      - History
      - Hourly
      - Station
      - Station
  /forecast/3hourly?city={city}&country={country}:
    get:
      summary: Get Forecast 3hourly City & Country
      description: Returns a 3-hourly forecast, where each point represents a three
        hour   period. Every point has a datetime string in the format "YYYY-MM-DD:HH".
        Time is UTC.
      operationId: returns-a-3hourly-forecast-where-each-point-represents-a-three-hour---period-every-point-has-a-datet
      x-api-path-slug: forecast3hourlycitycitycountrycountry-get
      parameters:
      - in: query
        name: callback
        description: Wraps return in jsonp callback
      - in: path
        name: city
        description: City search
      - in: path
        name: country
        description: Country Code (2 letter)
      - in: query
        name: days
        description: Number of days to return
      - in: query
        name: key
        description: Your registered API key
      - in: query
        name: lang
        description: 'Language (Default: English) See language field description'
      - in: query
        name: state
        description: Full name of state
      - in: query
        name: units
        description: Convert to units
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Forecast
      - 3hourly
      - City
      - City
      - '&country'
      - Country
  /forecast/3hourly?city_id={city_id}:
    get:
      summary: Get Forecast 3hourly City
      description: Returns a 3-hourly forecast, where each point represents a three
        hour   period. Every point has a datetime string in the format "YYYY-MM-DD:HH".
        Time is UTC.
      operationId: returns-a-3hourly-forecast-where-each-point-represents-a-three-hour---period-every-point-has-a-datet
      x-api-path-slug: forecast3hourlycity-idcity-id-get
      parameters:
      - in: query
        name: callback
        description: Wraps return in jsonp callback
      - in: path
        name: city_id
        description: City ID
      - in: query
        name: days
        description: Number of days to return
      - in: query
        name: key
        description: Your registered API key
      - in: query
        name: lang
        description: 'Language (Default: English) See language field description'
      - in: query
        name: units
        description: Convert to units
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Forecast
      - 3hourly
      - City
      - ""
      - City
  /forecast/3hourly?ip={ip}:
    get:
      summary: Get Forecast 3hourly IP
      description: Returns a 3-hourly forecast, where each point represents a three
        hour   period. Every point has a datetime string in the format "YYYY-MM-DD:HH".
        Time is UTC.
      operationId: returns-a-3hourly-forecast-where-each-point-represents-a-three-hour---period-every-point-has-a-datet
      x-api-path-slug: forecast3hourlyipip-get
      parameters:
      - in: query
        name: callback
        description: Wraps return in jsonp callback
      - in: query
        name: days
        description: Number of days to return
      - in: path
        name: ip
        description: IP address, or auto
      - in: query
        name: key
        description: Your registered API key
      - in: query
        name: lang
        description: 'Language (Default: English) See language field description'
      - in: query
        name: units
        description: Convert to units
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Forecast
      - 3hourly
      - Ip
      - Ip
  /forecast/3hourly?lat={lat}&lon={lon}:
    get:
      summary: Get Forecast 3hourly Lat & Lon
      description: Returns a 3-hourly forecast, where each point represents a three
        hour   period. Every point has a datetime string in the format "YYYY-MM-DD:HH".
        Time is UTC.
      operationId: returns-a-3hourly-forecast-where-each-point-represents-a-three-hour---period-every-point-has-a-datet
      x-api-path-slug: forecast3hourlylatlatlonlon-get
      parameters:
      - in: query
        name: callback
        description: Wraps return in jsonp callback
      - in: query
        name: days
        description: Number of days to return
      - in: query
        name: key
        description: Your registered API key
      - in: query
        name: lang
        description: 'Language (Default: English) See language field description'
      - in: path
        name: lat
        description: Latitude component of location
      - in: path
        name: lon
        description: Longitude component of location
      - in: query
        name: units
        description: Convert to units
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Forecast
      - 3hourly
      - Lat
      - Lat
      - '&lon'
      - Lon
  /forecast/3hourly?postal_code={postal_code}:
    get:
      summary: Get Forecast 3hourly Postla Code Code
      description: Returns a 3-hourly forecast, where each point represents a three
        hour period. Every point has a datetime string in the format "YYYY-MM-DD:HH".
        Time is UTC.
      operationId: returns-a-3hourly-forecast-where-each-point-represents-a-three-hour-period-every-point-has-a-datetim
      x-api-path-slug: forecast3hourlypostal-codepostal-code-get
      parameters:
      - in: query
        name: callback
        description: Wraps return in jsonp callback
      - in: query
        name: country
        description: Country Code (2 letter)
      - in: query
        name: days
        description: Number of days to return
      - in: query
        name: key
        description: Your registered API key
      - in: query
        name: lang
        description: 'Language (Default: English) See language field description'
      - in: path
        name: postal_code
        description: Postal Code
      - in: query
        name: units
        description: Convert to units
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Forecast
      - 3hourly
      - Postal
      - Code
      - Postal
      - Code
  /forecast/hourly?city={city}&country={country}:
    get:
      summary: Get Forecast Hourly City & Country
      description: '**(REQUIRED: Developer Plan or Higher)** Returns an hourly forecast,
        where each point represents a one hour   period. Every point has a datetime
        string in the format "YYYY-MM-DD:HH". Time is UTC. Accepts a city in the format
        of City,ST or City. The state, and country parameters can be provided to make
        the search more accurate.'
      operationId: required-developer-plan-or-higher-returns-an-hourly-forecast-where-each-point-represents-a-one-hour-
      x-api-path-slug: forecasthourlycitycitycountrycountry-get
      parameters:
      - in: query
        name: callback
        description: Wraps return in jsonp callback
      - in: path
        name: city
        description: City search
      - in: path
        name: country
        description: Country Code (2 letter)
      - in: query
        name: hours
        description: Number of hours to return
      - in: query
        name: key
        description: Your registered API key
      - in: query
        name: lang
        description: 'Language (Default: English) See language field description'
      - in: query
        name: state
        description: Full name of state
      - in: query
        name: units
        description: Convert to units
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Forecast
      - Hourly
      - City
      - City
      - '&country'
      - Country
  /forecast/hourly?city_id={city_id}:
    get:
      summary: Get Forecast Hourly City
      description: '**(REQUIRED: Developer Plan or Higher)** Returns an hourly forecast,
        where each point represents a one hour   period. Every point has a datetime
        string in the format "YYYY-MM-DD:HH". Time is UTC.'
      operationId: required-developer-plan-or-higher-returns-an-hourly-forecast-where-each-point-represents-a-one-hour-
      x-api-path-slug: forecasthourlycity-idcity-id-get
      parameters:
      - in: query
        name: callback
        description: Wraps return in jsonp callback
      - in: path
        name: city_id
        description: City ID
      - in: query
        name: hours
        description: Number of hours to return
      - in: query
        name: key
        description: Your registered API key
      - in: query
        name: lang
        description: 'Language (Default: English) See language field description'
      - in: query
        name: units
        description: Convert to units
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Forecast
      - Hourly
      - City
      - ""
      - City
  /forecast/hourly?ip={ip}:
    get:
      summary: Get Forecast Hourly IP
      description: '**(REQUIRED: Developer Plan or Higher)** Returns an hourly forecast,
        where each point represents a one hour period. Every point has a datetime
        string in the format "YYYY-MM-DD:HH". Time is UTC.'
      operationId: required-developer-plan-or-higher-returns-an-hourly-forecast-where-each-point-represents-a-one-hour-
      x-api-path-slug: forecasthourlyipip-get
      parameters:
      - in: query
        name: callback
        description: Wraps return in jsonp callback
      - in: query
        name: days
        description: Number of days to return
      - in: query
        name: hours
        description: Number of hours to return
      - in: path
        name: ip
        description: IP address, or auto
      - in: query
        name: key
        description: Your registered API key
      - in: query
        name: lang
        description: 'Language (Default: English) See language field description'
      - in: query
        name: units
        description: Convert to units
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Forecast
      - Hourly
      - Ip
      - Ip
  /forecast/hourly?lat={lat}&lon={lon}:
    get:
      summary: Get Forecast Hourly Lat & Lon
      description: '**(REQUIRED: Developer Plan or Higher)** Returns an hourly forecast,
        where each point represents a one hour period. Every point has a datetime
        string in the format "YYYY-MM-DD:HH". Time is UTC.'
      operationId: required-developer-plan-or-higher-returns-an-hourly-forecast-where-each-point-represents-a-one-hour-
      x-api-path-slug: forecasthourlylatlatlonlon-get
      parameters:
      - in: query
        name: callback
        description: Wraps return in jsonp callback
      - in: query
        name: hours
        description: Number of hours to return
      - in: query
        name: key
        description: Your registered API key
      - in: query
        name: lang
        description: 'Language (Default: English) See language field description'
      - in: path
        name: lat
        description: Latitude component of location
      - in: path
        name: lon
        description: Longitude component of location
      - in: query
        name: units
        description: Convert to units
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Forecast
      - Hourly
      - Lat
      - Lat
      - '&lon'
      - Lon
  /forecast/hourly?postal_code={postal_code}:
    get:
      summary: Get Forecast Hourly Postla Code Code
      description: '**(REQUIRED: Developer Plan or Higher)** Returns an hourly forecast,
        where each point represents a one hour   period. Every point has a datetime
        string in the format "YYYY-MM-DD:HH". Time is UTC.'
      operationId: required-developer-plan-or-higher-returns-an-hourly-forecast-where-each-point-represents-a-one-hour-
      x-api-path-slug: forecasthourlypostal-codepostal-code-get
      parameters:
      - in: query
        name: callback
        description: Wraps return in jsonp callback
      - in: query
        name: country
        description: Country Code (2 letter)
      - in: query
        name: hours
        description: Number of hours to return
      - in: query
        name: key
        description: Your registered API key
      - in: query
        name: lang
        description: 'Language (Default: English) See language field description'
      - in: path
        name: postal_code
        description: Postal Code
      - in: query
        name: units
        description: Convert to units
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Forecast
      - Hourly
      - Postal
      - Code
      - Postal
      - Code
  /history/hourly?city={city}&country={country}:
    get:
      summary: Get History Hourly City & Country
      description: Returns Historical Observations - Given a city in the format of
        City,ST or City. The state, and country parameters can be provided to make
        the search more accurate. **(LIMIT 1 day for Low Volume plans. LIMIT 7 days
        for Basic/Developer. LIMIT 30 days for Advanced/Advanced+/Enterprise)**
      operationId: returns-historical-observations--given-a-city-in-the-format-of-cityst-or-city-the-state-and-country-
      x-api-path-slug: historyhourlycitycitycountrycountry-get
      parameters:
      - in: query
        name: callback
        description: Wraps return in jsonp callback
      - in: path
        name: city
        description: City search
      - in: path
        name: country
        description: Country Code (2 letter)
      - in: query
        name: end_date
        description: End Date (YYYY-MM-DD or YYYY-MM-DD:HH)
      - in: query
        name: key
        description: Your registered API key
      - in: query
        name: lang
        description: 'Language (Default: English) See language field description'
      - in: query
        name: start_date
        description: Start Date (YYYY-MM-DD or YYYY-MM-DD:HH)
      - in: query
        name: state
        description: Full name of state
      - in: query
        name: units
        description: Convert to units
      responses:
        200:
          description: OK
      tags:
      - Weather
      - History
      - Hourly
      - City
      - City
      - '&country'
      - Country
  /history/hourly?city_id={city_id}:
    get:
      summary: Get History Hourly City
      description: Returns Historical Observations - Given a City ID. **(LIMIT 1 day
        for Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for
        Advanced/Advanced+/Enterprise)**
      operationId: returns-historical-observations--given-a-city-id-limit-1-day-for-low-volume-plans-limit-7-days-for-b
      x-api-path-slug: historyhourlycity-idcity-id-get
      parameters:
      - in: query
        name: callback
        description: Wraps return in jsonp callback
      - in: path
        name: city_id
        description: City ID
      - in: query
        name: end_date
        description: End Date (YYYY-MM-DD or YYYY-MM-DD:HH)
      - in: query
        name: key
        description: Your registered API key
      - in: query
        name: lang
        description: 'Language (Default: English) See language field description'
      - in: query
        name: start_date
        description: Start Date (YYYY-MM-DD or YYYY-MM-DD:HH)
      - in: query
        name: units
        description: Convert to units
      responses:
        200:
          description: OK
      tags:
      - Weather
      - History
      - Hourly
      - City
      - ""
      - City
  /history/hourly?ip={ip}:
    get:
      summary: Get History Hourly IP
      description: Returns Historical Observations - Given IP Address, or auto. **(LIMIT
        1 day for Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days
        for Advanced/Advanced+/Enterprise)**
      operationId: returns-historical-observations--given-ip-address-or-auto-limit-1-day-for-low-volume-plans-limit-7-d
      x-api-path-slug: historyhourlyipip-get
      parameters:
      - in: query
        name: callback
        description: Wraps return in jsonp callback
      - in: query
        name: end_date
        description: End Date (YYYY-MM-DD or YYYY-MM-DD:HH)
      - in: path
        name: ip
        description: IP Address, or auto
      - in: query
        name: key
        description: Your registered API key
      - in: query
        name: lang
        description: 'Language (Default: English) See language field description'
      - in: query
        name: start_date
        description: Start Date (YYYY-MM-DD or YYYY-MM-DD:HH)
      - in: query
        name: units
        description: Convert to units
      responses:
        200:
          description: OK
      tags:
      - Weather
      - History
      - Hourly
      - Ip
      - Ip
  /history/hourly?lat={lat}&lon={lon}:
    get:
      summary: Get History Hourly Lat & Lon
      description: Returns Historical Observations - Given a lat, and lon. **(LIMIT
        1 day for Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days
        for Advanced/Advanced+/Enterprise)**
      operationId: returns-historical-observations--given-a-lat-and-lon-limit-1-day-for-low-volume-plans-limit-7-days-f
      x-api-path-slug: historyhourlylatlatlonlon-get
      parameters:
      - in: query
        name: callback
        description: Wraps return in jsonp callback
      - in: query
        name: end_date
        description: End Date (YYYY-MM-DD or YYYY-MM-DD:HH)
      - in: query
        name: key
        description: Your registered API key
      - in: query
        name: lang
        description: 'Language (Default: English) See language field description'
      - in: path
        name: lat
        description: Latitude component of location
      - in: path
        name: lon
        description: Longitude component of location
      - in: query
        name: start_date
        description: Start Date (YYYY-MM-DD or YYYY-MM-DD:HH)
      - in: query
        name: units
        description: Convert to units
      responses:
        200:
          description: OK
      tags:
      - Weather
      - History
      - Hourly
      - Lat
      - Lat
      - '&lon'
      - Lon
  /history/hourly?postal_code={postal_code}:
    get:
      summary: Get History Hourly Postal Code
      description: Returns Historical Observations - Given a Postal Code. **(LIMIT
        1 day for Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days
        for Advanced/Advanced+/Enterprise)**
      operationId: returns-historical-observations--given-a-postal-code-limit-1-day-for-low-volume-plans-limit-7-days-f
      x-api-path-slug: historyhourlypostal-codepostal-code-get
      parameters:
      - in: query
        name: callback
        description: Wraps return in jsonp callback
      - in: query
        name: country
        description: Country Code (2 letter)
      - in: query
        name: end_date
        description: End Date (YYYY-MM-DD or YYYY-MM-DD:HH)
      - in: query
        name: key
        description: Your registered API key
      - in: query
        name: lang
        description: 'Language (Default: English) See language field description'
      - in: path
        name: postal_code
        description: Postal Code
      - in: query
        name: start_date
        description: Start Date (YYYY-MM-DD or YYYY-MM-DD:HH)
      - in: query
        name: units
        description: Convert to units
      responses:
        200:
          description: OK
      tags:
      - Weather
      - History
      - Hourly
      - Postal
      - Code
      - Postal
      - Code
  /history/hourly?station={station}:
    get:
      summary: Get History Hourly Station Station
      description: Returns Historical Observations - Given a station ID. **(LIMIT
        1 day for Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days
        for Advanced/Advanced+/Enterprise)**
      operationId: returns-historical-observations--given-a-station-id-limit-1-day-for-low-volume-plans-limit-7-days-fo
      x-api-path-slug: historyhourlystationstation-get
      parameters:
      - in: query
        name: callback
        description: Wraps return in jsonp callback
      - in: query
        name: end_date
        description: End Date (YYYY-MM-DD or YYYY-MM-DD:HH)
      - in: query
        name: key
        description: Your registered API key
      - in: query
        name: lang
        description: 'Language (Default: English) See language field description'
      - in: query
        name: start_date
        description: Start Date (YYYY-MM-DD or YYYY-MM-DD:HH)
      - in: path
        name: station
        description: Station ID
      - in: query
        name: units
        description: Convert to units
      responses:
        200:
          description: OK
      tags:
      - Weather
      - History
      - Hourly
      - Station
      - Station
---