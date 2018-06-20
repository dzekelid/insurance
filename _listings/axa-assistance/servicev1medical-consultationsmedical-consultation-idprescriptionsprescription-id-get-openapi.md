---
swagger: "2.0"
x-collection-name: AXA Assistance
x-complete: 0
info:
  title: AXA Assistance Provides detail of a prescription
  description: Provides detail of a prescription
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
  /network/vexp/roadside_providers/{provider_id}:
    get:
      summary: Gets information of roadside provider.
      description: Gets information of roadside provider.
      operationId: getNetworkVexpRoadside_providersProvider_id
      x-api-path-slug: networkvexproadside-providersprovider-id-get
      parameters:
      - in: path
        name: provider_id
        description: Provider unique id
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - information
      - of
      - roadside
      - provider.
  /ondemand/v1/medical_providers/kinds:
    get:
      summary: 'Retrieve all medical provider kinds available for search (Ex: pharmacy,
        hospital ...)'
      description: 'Retrieve all medical provider kinds available for search (Ex:
        pharmacy, hospital ...)'
      operationId: getOndemandV1Medical_providersKinds
      x-api-path-slug: ondemandv1medical-providerskinds-get
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
      - medical
      - provider
      - kindAssistance
      - availablesearch
      - '(Ex:'
      - pharmacy
      - ""
      - hospital
      - '...)'
  /ondemand/v1/medical_providers/search:
    get:
      summary: Search for medical providers
      description: Search for medical providers
      operationId: getOndemandV1Medical_providersSearch
      x-api-path-slug: ondemandv1medical-providerssearch-get
      parameters:
      - in: header
        name: accept-language
        description: Language/Country
      - in: query
        name: kind
        description: Provider kind
      - in: query
        name: lat
        description: Latitude
      - in: query
        name: lng
        description: Longitude
      - in: query
        name: speciality
        description: Speciality
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Searchmedical
      - providers
  /ondemand/v1/medical_providers/specialities:
    get:
      summary: 'Retrieve all medical provider specialities available for search (Ex:
        cardiology, dentist ...)'
      description: 'Retrieve all medical provider specialities available for search
        (Ex: cardiology, dentist ...)'
      operationId: getOndemandV1Medical_providersSpecialities
      x-api-path-slug: ondemandv1medical-providersspecialities-get
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
      - medical
      - provider
      - specialitieAssistance
      - availablesearch
      - '(Ex:'
      - cardiology
      - ""
      - dentist
      - '...)'
  /service/v1/medical_consultations/{medical_consultation_id}:
    get:
      summary: Provides detail of a medical consultation
      description: Provides detail of a medical consultation
      operationId: getServiceV1Medical_consultationsMedical_consultation_id
      x-api-path-slug: servicev1medical-consultationsmedical-consultation-id-get
      parameters:
      - in: path
        name: medical_consultation_id
        description: ID of the medical consultation
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - ProvideAssistance
      - detail
      - ofmedical
      - consultation
    patch:
      summary: Updates a medical consultation
      description: Updates a medical consultation
      operationId: patchServiceV1Medical_consultationsMedical_consultation_id
      x-api-path-slug: servicev1medical-consultationsmedical-consultation-id-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: medical_consultation_id
        description: ID of the medical consultation
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - smedical
      - consultation
  /information/v1/countries/{country_id}/security_cards:
    get:
      summary: Retrieve security information for a country
      description: Retrieve security information for a country
      operationId: getInformationV1CountriesCountry_idSecurity_cards
      x-api-path-slug: informationv1countriescountry-idsecurity-cards-get
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
      - Retrieve
      - security
      - informationa
      - country
  /information/v1/countries/{country_id}/health_cards:
    get:
      summary: Retrieve health information for a country
      description: Retrieve health information for a country
      operationId: getInformationV1CountriesCountry_idHealth_cards
      x-api-path-slug: informationv1countriescountry-idhealth-cards-get
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
      - Retrieve
      - health
      - informationa
      - country
  /information/v1/countries/{country_id}/alerts:
    get:
      summary: Retrieve the latest alerts for a specified country
      description: Retrieve the latest alerts for a specified country
      operationId: getInformationV1CountriesCountry_idAlerts
      x-api-path-slug: informationv1countriescountry-idalerts-get
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
      - Retrieve
      - the
      - latest
      - alertsa
      - specified
      - country
  /service/vexp/roadside/assignments/{assignment_id}:
    get:
      summary: Gets assignment information.
      description: Gets assignment information.
      operationId: getServiceVexpRoadsideAssignmentsAssignment_id
      x-api-path-slug: servicevexproadsideassignmentsassignment-id-get
      parameters:
      - in: path
        name: assignment_id
        description: Assignment unique identifier
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - assignment
      - information.
  /sales/v1/individual/appliance/certificates/{certificate_id}:
    get:
      summary: Get appliance (Extended warranty, purchase insurance ) certificate
        details.
      description: Get appliance (Extended warranty, purchase insurance ) certificate
        details.
      operationId: getSalesV1IndividualApplianceCertificatesCertificate_id
      x-api-path-slug: salesv1individualappliancecertificatescertificate-id-get
      parameters:
      - in: header
        name: accept-language
        description: Accepted language, IANA language codification
      - in: path
        name: certificate_id
        description: Certificate unique identifier
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - appliance
      - (Extended
      - warranty
      - ""
      - purchase
      - insurance
      - )
      - certificate
      - details.
  /sales/v1/individual/car_rental/certificates/{certificate_id}:
    get:
      summary: Gets the car rental certificate details.
      description: Gets the car rental certificate details.
      operationId: getSalesV1IndividualCar_rentalCertificatesCertificate_id
      x-api-path-slug: salesv1individualcar-rentalcertificatescertificate-id-get
      parameters:
      - in: header
        name: accept-language
        description: Accepted language, IANA language codification
      - in: path
        name: certificate_id
        description: Certificate unique identifier
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - car
      - rental
      - certificate
      - details.
  /sales/v1/individual/travel/certificates/{certificate_id}:
    get:
      summary: Gets the travel certificate details.
      description: Gets the travel certificate details.
      operationId: getSalesV1IndividualTravelCertificatesCertificate_id
      x-api-path-slug: salesv1individualtravelcertificatescertificate-id-get
      parameters:
      - in: header
        name: accept-language
        description: Accepted language, IANA language codification
      - in: path
        name: certificate_id
        description: Certificate unique identifier
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - travel
      - certificate
      - details.
  /service/v1/medical_consultations/{medical_consultation_id}/prescriptions/{prescription_id}:
    get:
      summary: Provides detail of a prescription
      description: Provides detail of a prescription
      operationId: getServiceV1Medical_consultationsMedical_consultation_idPrescriptionsPrescription_id
      x-api-path-slug: servicev1medical-consultationsmedical-consultation-idprescriptionsprescription-id-get
      parameters:
      - in: path
        name: medical_consultation_id
        description: ID of the medical consultation
      - in: path
        name: prescription_id
        description: ID of the prescription
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - ProvideAssistance
      - detail
      - ofprescription
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