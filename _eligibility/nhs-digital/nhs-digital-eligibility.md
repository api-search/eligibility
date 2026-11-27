---
api_specs:
- filename: nhs-digital-booking-api-openapi.yml
  format: yaml
  label: NHS Digital Booking API
  slug: nhs-digital-booking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nhs-digital/openapi/nhs-digital-booking-api-openapi.yml
- filename: nhs-digital-communication-api-openapi.yml
  format: yaml
  label: NHS Digital Communication API
  slug: nhs-digital-communication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nhs-digital/openapi/nhs-digital-communication-api-openapi.yml
- filename: nhs-digital-message-api-openapi.yml
  format: yaml
  label: NHS Digital Message API
  slug: nhs-digital-message-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nhs-digital/openapi/nhs-digital-message-api-openapi.yml
- filename: nhs-digital-metadata-api-openapi.yml
  format: yaml
  label: NHS Digital Metadata API
  slug: nhs-digital-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nhs-digital/openapi/nhs-digital-metadata-api-openapi.yml
- filename: nhs-digital-r4-api-openapi.yml
  format: yaml
  label: NHS Digital R4 API
  slug: nhs-digital-r4-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nhs-digital/openapi/nhs-digital-r4-api-openapi.yml
- filename: nhs-digital-referral-api-openapi.yml
  format: yaml
  label: NHS Digital Referral API
  slug: nhs-digital-referral-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nhs-digital/openapi/nhs-digital-referral-api-openapi.yml
- filename: nhs-digital-slots-api-openapi.yml
  format: yaml
  label: NHS Digital Slots API
  slug: nhs-digital-slots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nhs-digital/openapi/nhs-digital-slots-api-openapi.yml
- filename: nhs-digital-stu3-api-openapi.yml
  format: yaml
  label: NHS Digital STU3 API
  slug: nhs-digital-stu3-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nhs-digital/openapi/nhs-digital-stu3-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The API Service is intended for use in association with products to be used in England.
  entity_types:
  - text: We are giving you personally the right to access and use the API Service.
    type: individual
  - text: Your organisation is subject to the terms of its Connection Agreement.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Live data and production access conditional
    text: Your receipt of security credentials allowing access to the APIs in production and non-production environments and live data is conditional upon your organisation’s successful Onboarding and Connection Agreement.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: issue of security credentials allowing access to the APIs in production and non-production environments and live data is given at NHS England’s sole discretion
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: NHS Digital
provenance_date: '2026-11-10'
provider_name: NHS Digital
provider_slug: nhs-digital
slug: nhs-digital-eligibility
source_date: '2026-11-10'
source_filename: nhs-digital-eligibility.yml
source_heading: Eligibility
source_page: https://onboarding.prod.api.platform.nhs.uk/PolicyPages/TermsOfUsePolicy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NHS Digital\naid: nhs-digital\nurl: https://onboarding.prod.api.platform.nhs.uk/PolicyPages/TermsOfUsePolicy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The API Service is intended for use in association with products to be used in England.\nentity_types:\n- type: individual\n  text: We are giving you personally the right to access and use the API Service.\n- type: business\n  text: Your organisation is subject to the terms of its Connection Agreement.\nrestricted_uses:\n- summary: Live data and production access conditional\n  text: Your receipt of security credentials allowing\
  \ access to the APIs in production and non-production environments\n    and live data is conditional upon your organisation’s successful Onboarding and Connection Agreement.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: issue of security credentials allowing access to the APIs in production and non-production environments\n    and live data is given at NHS England’s sole discretion\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nhs-digital/eligibility/nhs-digital-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from NHS Digital's own page on 2026-11-10.
synthetic: false
tags:
- NHS
- Health
- FHIR
- United Kingdom
- Patient Demographics
- Prescriptions
- Referrals
- Clinical Data
- Digital Health
- Government
---
