---
swagger: "2.0"
x-collection-name: AXA Assistance
x-complete: 0
info:
  title: AXA Assistance Creates a declaration for a glaziery damage
  description: Creates a declaration for a glaziery damage
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
    patch:
      summary: Updates a prescription
      description: Updates a prescription
      operationId: patchServiceV1Medical_consultationsMedical_consultation_idPrescriptionsPrescription_id
      x-api-path-slug: servicev1medical-consultationsmedical-consultation-idprescriptionsprescription-id-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
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
      - sprescription
  /user/v1/identities/{identity_id}/channels/sms:
    get:
      summary: Get channel
      description: Get channel
      operationId: getUserV1IdentitiesIdentity_idChannelsSms
      x-api-path-slug: userv1identitiesidentity-idchannelssms-get
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - channel
    put:
      summary: Update channel
      description: Update channel
      operationId: putUserV1IdentitiesIdentity_idChannelsSms
      x-api-path-slug: userv1identitiesidentity-idchannelssms-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: identity_id
        description: ID of the identity
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - channel
  /assistance/v1/home/electric_damage/declarations/{declaration_id}/policy_holders:
    get:
      summary: Gets the policy holders details for the electric damage
      description: Gets the policy holders details for the electric damage
      operationId: getAssistanceV1HomeElectric_damageDeclarationsDeclaration_idPolicy_holders
      x-api-path-slug: assistancev1homeelectric-damagedeclarationsdeclaration-idpolicy-holders-get
      parameters:
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - policy
      - holderAssistance
      - detailsthe
      - electric
      - damage
  /assistance/v1/home/gas_damage/declarations/{declaration_id}/policy_holders:
    get:
      summary: Gets the policy holders details for the gas damage
      description: Gets the policy holders details for the gas damage
      operationId: getAssistanceV1HomeGas_damageDeclarationsDeclaration_idPolicy_holders
      x-api-path-slug: assistancev1homegas-damagedeclarationsdeclaration-idpolicy-holders-get
      parameters:
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - policy
      - holderAssistance
      - detailsthe
      - gaAssistance
      - damage
  /assistance/v1/home/glaziery_damage/declarations/{declaration_id}/policy_holders:
    get:
      summary: Gets the information linked to the policy holder of the glaziery damage
        declaration
      description: Gets the information linked to the policy holder of the glaziery
        damage declaration
      operationId: getAssistanceV1HomeGlaziery_damageDeclarationsDeclaration_idPolicy_holders
      x-api-path-slug: assistancev1homeglaziery-damagedeclarationsdeclaration-idpolicy-holders-get
      parameters:
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - information
      - linked
      - to
      - the
      - policy
      - holder
      - of
      - the
      - glaziery
      - damage
      - Declarations
  /assistance/v1/home/home_appliance_damage/declarations/{declaration_id}/policy_holders:
    get:
      summary: Gets the information linked to the policy holder of the home appliance
        damage declaration
      description: Gets the information linked to the policy holder of the home appliance
        damage declaration
      operationId: getAssistanceV1HomeHome_appliance_damageDeclarationsDeclaration_idPolicy_holders
      x-api-path-slug: assistancev1homehome-appliance-damagedeclarationsdeclaration-idpolicy-holders-get
      parameters:
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - information
      - linked
      - to
      - the
      - policy
      - holder
      - of
      - the
      - home
      - appliance
      - damage
      - Declarations
  /assistance/v1/home/locksmithing_damage/declarations/{declaration_id}/policy_holders:
    get:
      summary: Gets the information linked to the policy holder of the locksmithing
        damage declaration
      description: Gets the information linked to the policy holder of the locksmithing
        damage declaration
      operationId: getAssistanceV1HomeLocksmithing_damageDeclarationsDeclaration_idPolicy_holders
      x-api-path-slug: assistancev1homelocksmithing-damagedeclarationsdeclaration-idpolicy-holders-get
      parameters:
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - information
      - linked
      - to
      - the
      - policy
      - holder
      - of
      - the
      - locksmithing
      - damage
      - Declarations
  /assistance/v1/home/water_damage/declarations/{declaration_id}/policy_holders:
    get:
      summary: Gets the information related to each the policy holder of the water
        damage declaration
      description: Gets the information related to each the policy holder of the water
        damage declaration
      operationId: getAssistanceV1HomeWater_damageDeclarationsDeclaration_idPolicy_holders
      x-api-path-slug: assistancev1homewater-damagedeclarationsdeclaration-idpolicy-holders-get
      parameters:
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - information
      - related
      - to
      - each
      - the
      - policy
      - holder
      - of
      - the
      - water
      - damage
      - Declarations
  /service/v1/medical_consultations/{medical_consultation_id}/prescriptions/{prescription_id}/attachments/{attachment_id}:
    get:
      summary: Retrieve an attachment
      description: Retrieve an attachment
      operationId: getServiceV1Medical_consultationsMedical_consultation_idPrescriptionsPrescription_idAttachmentsAttac
      x-api-path-slug: servicev1medical-consultationsmedical-consultation-idprescriptionsprescription-idattachmentsattachment-id-get
      parameters:
      - in: path
        name: attachment_id
        description: ID of the attachment
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
      - Retrieveattachment
  /service/v1/medical_consultations:
    post:
      summary: Creates a medical consultation.
      description: Creates a medical consultation.
      operationId: postServiceV1Medical_consultations
      x-api-path-slug: servicev1medical-consultations-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Createsmedical
      - consultation.
  /insurance/vexp/appliance/claims:
    post:
      summary: Requests to create a claim related to an appliance.
      description: Requests to create a claim related to an appliance.
      operationId: postInsuranceVexpApplianceClaims
      x-api-path-slug: insurancevexpapplianceclaims-post
      parameters:
      - in: header
        name: accept-language
        description: Accepted language, IANA language codification
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - RequestAssistance
      - to
      - createclaim
      - related
      - toappliance.
  /insurance/vexp/car_rental/claims:
    post:
      summary: Requests to create a claim related to a car rental.
      description: Requests to create a claim related to a car rental.
      operationId: postInsuranceVexpCar_rentalClaims
      x-api-path-slug: insurancevexpcar-rentalclaims-post
      parameters:
      - in: header
        name: accept-language
        description: Accepted language, IANA language codification
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - RequestAssistance
      - to
      - createclaim
      - related
      - tocar
      - rental.
  /insurance/vexp/corporate_liability/claims:
    post:
      summary: Requests to create a claim related to a corporate liability.
      description: Requests to create a claim related to a corporate liability.
      operationId: postInsuranceVexpCorporate_liabilityClaims
      x-api-path-slug: insurancevexpcorporate-liabilityclaims-post
      parameters:
      - in: header
        name: accept-language
        description: Accepted language, IANA language codification
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - RequestAssistance
      - to
      - createclaim
      - related
      - tocorporate
      - liability.
  /insurance/vexp/delayed_luggage/claims:
    post:
      summary: Requests to create a claim related to a delayed luggage.
      description: Requests to create a claim related to a delayed luggage.
      operationId: postInsuranceVexpDelayed_luggageClaims
      x-api-path-slug: insurancevexpdelayed-luggageclaims-post
      parameters:
      - in: header
        name: accept-language
        description: Accepted language, IANA language codification
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - RequestAssistance
      - to
      - createclaim
      - related
      - todelayed
      - luggage.
  /insurance/vexp/delayed_trip/claims:
    post:
      summary: Requests to create a claim related to a delayed trip.
      description: Requests to create a claim related to a delayed trip.
      operationId: postInsuranceVexpDelayed_tripClaims
      x-api-path-slug: insurancevexpdelayed-tripclaims-post
      parameters:
      - in: header
        name: accept-language
        description: Accepted language, IANA language codification
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - RequestAssistance
      - to
      - createclaim
      - related
      - todelayed
      - trip.
  /insurance/vexp/lost_baggage/claims:
    post:
      summary: Requests to create a claim related to a lost baggage.
      description: Requests to create a claim related to a lost baggage.
      operationId: postInsuranceVexpLost_baggageClaims
      x-api-path-slug: insurancevexplost-baggageclaims-post
      parameters:
      - in: header
        name: accept-language
        description: Accepted language, IANA language codification
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - RequestAssistance
      - to
      - createclaim
      - related
      - tolost
      - baggage.
  /insurance/vexp/missed_flight/claims:
    post:
      summary: Requests to create a claim related to a missed flight.
      description: Requests to create a claim related to a missed flight.
      operationId: postInsuranceVexpMissed_flightClaims
      x-api-path-slug: insurancevexpmissed-flightclaims-post
      parameters:
      - in: header
        name: accept-language
        description: Accepted language, IANA language codification
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - RequestAssistance
      - to
      - createclaim
      - related
      - tomissed
      - flight.
  /insurance/vexp/price_protection/claims:
    post:
      summary: Requests to create a claim related to a price protection.
      description: Requests to create a claim related to a price protection.
      operationId: postInsuranceVexpPrice_protectionClaims
      x-api-path-slug: insurancevexpprice-protectionclaims-post
      parameters:
      - in: header
        name: accept-language
        description: Accepted language, IANA language codification
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - RequestAssistance
      - to
      - createclaim
      - related
      - toprice
      - protection.
  /insurance/vexp/stolen_cash/claims:
    post:
      summary: Requests to create a claim related to a stolen cash.
      description: Requests to create a claim related to a stolen cash.
      operationId: postInsuranceVexpStolen_cashClaims
      x-api-path-slug: insurancevexpstolen-cashclaims-post
      parameters:
      - in: header
        name: accept-language
        description: Accepted language, IANA language codification
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - RequestAssistance
      - to
      - createclaim
      - related
      - tostolen
      - cash.
  /insurance/vexp/travel_accident/claims:
    post:
      summary: Requests to create a claim related to a travel accident.
      description: Requests to create a claim related to a travel accident.
      operationId: postInsuranceVexpTravel_accidentClaims
      x-api-path-slug: insurancevexptravel-accidentclaims-post
      parameters:
      - in: header
        name: accept-language
        description: Accepted language, IANA language codification
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - RequestAssistance
      - to
      - createclaim
      - related
      - totravel
      - accident.
  /insurance/vexp/trip/claims:
    post:
      summary: Requests to create a claim related to a trip.
      description: Requests to create a claim related to a trip.
      operationId: postInsuranceVexpTripClaims
      x-api-path-slug: insurancevexptripclaims-post
      parameters:
      - in: header
        name: accept-language
        description: Accepted language, IANA language codification
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - RequestAssistance
      - to
      - createclaim
      - related
      - totrip.
  /insurance/vexp/trip_cancellation/claims:
    post:
      summary: Requests to create a claim related to a trip cancellation.
      description: Requests to create a claim related to a trip cancellation.
      operationId: postInsuranceVexpTrip_cancellationClaims
      x-api-path-slug: insurancevexptrip-cancellationclaims-post
      parameters:
      - in: header
        name: accept-language
        description: Accepted language, IANA language codification
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - RequestAssistance
      - to
      - createclaim
      - related
      - totrip
      - cancellation.
  /service/vexp/roadside/assignments:
    post:
      summary: Creates new assignment.
      description: Creates new assignment.
      operationId: postServiceVexpRoadsideAssignments
      x-api-path-slug: servicevexproadsideassignments-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - CreateAssistance
      - new
      - assignment.
  /user/v1/identities/forgot_password:
    post:
      summary: Forgot identity password
      description: Forgot identity password
      operationId: postUserV1IdentitiesForgot_password
      x-api-path-slug: userv1identitiesforgot-password-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Forgot
      - identity
      - password
  /user/v1/identities/register:
    post:
      summary: Register identity
      description: Register identity
      operationId: postUserV1IdentitiesRegister
      x-api-path-slug: userv1identitiesregister-post
      parameters:
      - in: header
        name: accept-language
        description: Language/Country
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Register
      - identity
  /assistance/v1/home/electric_damage/declarations:
    post:
      summary: Create a declaration for an electric damage
      description: Create a declaration for an electric damage
      operationId: postAssistanceV1HomeElectric_damageDeclarations
      x-api-path-slug: assistancev1homeelectric-damagedeclarations-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - CreateDeclarationsan
      - electric
      - damage
  /assistance/v1/home/gas_damage/declarations:
    post:
      summary: Creates a declaration for a gas damage
      description: Creates a declaration for a gas damage
      operationId: postAssistanceV1HomeGas_damageDeclarations
      x-api-path-slug: assistancev1homegas-damagedeclarations-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - CreatesDeclarationsa
      - gaAssistance
      - damage
  /assistance/v1/home/glaziery_damage/declarations:
    post:
      summary: Creates a declaration for a glaziery damage
      description: Creates a declaration for a glaziery damage
      operationId: postAssistanceV1HomeGlaziery_damageDeclarations
      x-api-path-slug: assistancev1homeglaziery-damagedeclarations-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - CreatesDeclarationsa
      - glaziery
      - damage
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