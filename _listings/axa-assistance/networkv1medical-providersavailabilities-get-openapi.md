---
swagger: "2.0"
x-collection-name: AXA Assistance
x-complete: 0
info:
  title: AXA Assistance Gets the availabilities of medical providers.
  description: Gets the availabilities of medical providers.
  version: 1.0.0
host: sandbox.api.axa-assistance.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /assistance/version:
    get:
      summary: Provide basic details about the current deployed version of the assistance
        API
      description: Provide basic details about the current deployed version of the
        assistance API
      operationId: getAssistanceVersion
      x-api-path-slug: assistanceversion-get
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Provide
      - basic
      - detailAssistance
      - about
      - the
      - current
      - deployed
      - version
      - of
      - the
      - assistance
      - API
  /information/version:
    get:
      summary: Provide basic details about the current deployed version of the information
        API
      description: Provide basic details about the current deployed version of the
        information API
      operationId: getInformationVersion
      x-api-path-slug: informationversion-get
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Provide
      - basic
      - detailAssistance
      - about
      - the
      - current
      - deployed
      - version
      - of
      - the
      - information
      - API
  /insurance/version:
    get:
      summary: Provide basic details about the current deployed version of the insurance
        API
      description: Provide basic details about the current deployed version of the
        insurance API
      operationId: getInsuranceVersion
      x-api-path-slug: insuranceversion-get
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Provide
      - basic
      - detailAssistance
      - about
      - the
      - current
      - deployed
      - version
      - of
      - the
      - insurance
      - API
  /network/version:
    get:
      summary: Provide basic details about the current deployed version of the network
        API
      description: Provide basic details about the current deployed version of the
        network API
      operationId: getNetworkVersion
      x-api-path-slug: networkversion-get
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Provide
      - basic
      - detailAssistance
      - about
      - the
      - current
      - deployed
      - version
      - of
      - the
      - network
      - API
  /ondemand/version:
    get:
      summary: Provide basic details about the current deployed version of the on
        demand API
      description: Provide basic details about the current deployed version of the
        on demand API
      operationId: getOndemandVersion
      x-api-path-slug: ondemandversion-get
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Provide
      - basic
      - detailAssistance
      - about
      - the
      - current
      - deployed
      - version
      - of
      - the
      - "on"
      - demand
      - API
  /sales/version:
    get:
      summary: Provide basic details about the current deployed version of the sales
        API
      description: Provide basic details about the current deployed version of the
        sales API
      operationId: getSalesVersion
      x-api-path-slug: salesversion-get
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Provide
      - basic
      - detailAssistance
      - about
      - the
      - current
      - deployed
      - version
      - of
      - the
      - saleAssistance
      - API
  /service/version:
    get:
      summary: Provide basic details about the current deployed version of the service
        API
      description: Provide basic details about the current deployed version of the
        service API
      operationId: getServiceVersion
      x-api-path-slug: serviceversion-get
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Provide
      - basic
      - detailAssistance
      - about
      - the
      - current
      - deployed
      - version
      - of
      - the
      - service
      - API
  /user/version:
    get:
      summary: Provide basic details about the current deployed version of the User
        API
      description: Provide basic details about the current deployed version of the
        User API
      operationId: getUserVersion
      x-api-path-slug: userversion-get
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Provide
      - basic
      - detailAssistance
      - about
      - the
      - current
      - deployed
      - version
      - of
      - the
      - User
      - API
  /information/v1/countries:
    get:
      summary: Retrieve all countries
      description: Retrieve all countries
      operationId: getInformationV1Countries
      x-api-path-slug: informationv1countries-get
      parameters:
      - in: header
        name: accept-language
        description: Language/Country
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Retrieve
      - all
      - countries
  /assistance/v1/home/cases:
    get:
      summary: Gets details of cases
      description: Gets details of cases
      operationId: getAssistanceV1HomeCases
      x-api-path-slug: assistancev1homecases-get
      parameters:
      - in: query
        name: declaration_id
        description: ID of the declaration which has trigger the cases
      - in: query
        name: lastname
        description: Lastname of the person associated to the case
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - detailAssistance
      - of
      - cases
  /information/v1/countries/alerts:
    get:
      summary: Retrieve the latest alerts worldwide
      description: Retrieve the latest alerts worldwide
      operationId: getInformationV1CountriesAlerts
      x-api-path-slug: informationv1countriesalerts-get
      parameters:
      - in: header
        name: accept-language
        description: Language/Country
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Retrieve
      - the
      - latest
      - alertAssistance
      - worldwide
  /information/v1/countries/{country_id}:
    get:
      summary: Retrieve a country detail
      description: Retrieve a country detail
      operationId: getInformationV1CountriesCountry_id
      x-api-path-slug: informationv1countriescountry-id-get
      parameters:
      - in: header
        name: accept-language
        description: Language/Country
      - in: path
        name: country_id
        description: country id
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Retrievecountry
      - detail
  /information/vexp/roadside/workshops:
    get:
      summary: Gets list of nearest workshops.
      description: Gets list of nearest workshops.
      operationId: getInformationVexpRoadsideWorkshops
      x-api-path-slug: informationvexproadsideworkshops-get
      parameters:
      - in: query
        name: latitude
        description: Latitude of the location around which to search, latitude to
          be provided in WGS84 format
      - in: query
        name: longitude
        description: Longitude of the location around which to search, longitude to
          be provided in WGS84 format
      - in: query
        name: radius
        description: Maximum distance around
      - in: query
        name: radius_unit
        description: Unit of radius, ISO-20022 Unit Of Measure 2 Code (required if
          radius is provided)
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - list
      - of
      - nearest
      - workshops.
  /network/v1/medical_providers/availabilities:
    get:
      summary: Gets the availabilities of medical providers.
      description: Gets the availabilities of medical providers.
      operationId: getNetworkV1Medical_providersAvailabilities
      x-api-path-slug: networkv1medical-providersavailabilities-get
      parameters:
      - in: query
        name: end_date
        description: End date and time of the availability search - UTC datetime,
          RFC3339 format (YYYY-MM-DDTHH:mmZ)
      - in: query
        name: start_date
        description: Beginning date and time of the availability search - UTC datetime,
          RFC3339 format (YYYY-MM-DDTHH:mmZ)
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - availabilitieAssistance
      - of
      - medical
      - providers.
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