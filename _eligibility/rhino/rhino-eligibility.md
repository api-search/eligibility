---
api_specs:
- filename: rhino-authentication-api-openapi.yml
  format: yaml
  label: Rhino Authentication API
  slug: rhino-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rhino/openapi/rhino-authentication-api-openapi.yml
- filename: rhino-partnerapi-v2-test-resident-api-openapi.yml
  format: yaml
  label: Rhino Partner Api::V2::Test::Resident API
  slug: rhino-partnerapi-v2-test-resident-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rhino/openapi/rhino-partnerapi-v2-test-resident-api-openapi.yml
- filename: rhino-partnerapi-v2-test-sayrhinouser-api-openapi.yml
  format: yaml
  label: Rhino Partner Api::V2::Test::Sayrhino User API
  slug: rhino-partnerapi-v2-test-sayrhinouser-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rhino/openapi/rhino-partnerapi-v2-test-sayrhinouser-api-openapi.yml
- filename: rhino-prospects-api-openapi.yml
  format: yaml
  label: Rhino Prospects API
  slug: rhino-prospects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rhino/openapi/rhino-prospects-api-openapi.yml
- filename: rhino-webhooks-api-openapi.yml
  format: yaml
  label: Rhino Webhooks API
  slug: rhino-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rhino/openapi/rhino-webhooks-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Greenlight is not available in HI, MT, ND or WY for SDA coverage; users in embargoed countries or on the SDN list may not engage in commercial activities.
  entity_types:
  - text: You agree that you will not use the Website or Services if you are under 18.
    type: individual
  minimum_age:
    text: You agree that you will not use the Website or Services if you are under 18.
    value: '18'
  restricted_uses:
  - summary: Illegal purposes and marijuana-related business
    text: You shall not use these services in connection with any marijuana related business, including without limitation the leasing of real estate for purposes of operating a marijuana related business
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Coverage is subject to underwriting approval, and may not be available to all persons, even if offered in your state.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Rhino
provenance_date: '2026-11-10'
provider_name: Rhino
provider_slug: rhino
slug: rhino-eligibility
source_date: '2026-11-10'
source_filename: rhino-eligibility.yml
source_heading: Eligibility
source_page: https://www.greenlightrent.com/terms_of_service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rhino\naid: rhino\nurl: https://www.greenlightrent.com/terms_of_service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Greenlight is not available in HI, MT, ND or WY for SDA coverage; users in embargoed countries or on the\n    SDN list may not engage in commercial activities.\nentity_types:\n- type: individual\n  text: You agree that you will not use the Website or Services if you are under 18.\nrestricted_uses:\n- summary: Illegal purposes and marijuana-related business\n  text: You shall not use these services in connection with any marijuana related business, including without\
  \ limitation\n    the leasing of real estate for purposes of operating a marijuana related business\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Coverage is subject to underwriting approval, and may not be available to all persons, even if offered in\n    your state.\nminimum_age:\n  value: '18'\n  text: You agree that you will not use the Website or Services if you are under 18.\n"
source_yaml_url: https://artifacts.apis.io/rhino/eligibility/rhino-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Rhino's own page on 2026-11-10.
synthetic: false
tags:
- Insurance
- Insurtech
- Real Estate
- Property Management
- Rentals
- Security Deposits
- Renters Insurance
- Webhook
- Partner API
---
