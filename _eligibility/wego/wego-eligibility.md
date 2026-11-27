---
api_specs:
- filename: wego-countries-api-openapi.yml
  format: yaml
  label: Wego Countries API
  slug: wego-countries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wego/openapi/wego-countries-api-openapi.yml
- filename: wego-feedback-api-openapi.yml
  format: yaml
  label: Wego Feedback API
  slug: wego-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wego/openapi/wego-feedback-api-openapi.yml
- filename: wego-flights-api-openapi.yml
  format: yaml
  label: Wego Flights API
  slug: wego-flights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wego/openapi/wego-flights-api-openapi.yml
- filename: wego-health-api-openapi.yml
  format: yaml
  label: Wego Health API
  slug: wego-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wego/openapi/wego-health-api-openapi.yml
- filename: wego-hotels-api-openapi.yml
  format: yaml
  label: Wego Hotels API
  slug: wego-hotels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wego/openapi/wego-hotels-api-openapi.yml
- filename: wego-places-api-openapi.yml
  format: yaml
  label: Wego Places API
  slug: wego-places-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wego/openapi/wego-places-api-openapi.yml
- filename: wego-user-api-openapi.yml
  format: yaml
  label: Wego User API
  slug: wego-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wego/openapi/wego-user-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - EG
    - IN
    - PK
    - SA
    - AE
    text: 'Users in the following countries will be served by the following Wego entities: Egypt: Wego Travel (under license 730) India: Wego Search Technologies Private Limited Pakistan: Wego Travel & Tourism (Private) Ltd Saudi Arabia: Wego Saudi for Travel and Tourism Services United Arab Emirates: Wego ME Travel & Tourism'
  entity_types:
  - text: You agree that you will use the Services solely for your own personal, non-commercial, lawful purposes
    type: individual
  minimum_age:
    text: You must be a resident of the Kingdom of Saudi Arabia and at least 18 years of age to use STC Pay.
    value: '18'
  restricted_uses:
  - summary: Unlawful, speculative or fraudulent reservations
    text: not for any purpose that is unlawful or prohibited by these Terms, including without limitation, to make any speculative, false or fraudulent reservation
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Certain cryptocurrency transactions require identity verification (ID upload) as per regulatory requirements, which are beyond Wego’s control
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Wego
provenance_date: '2026-11-10'
provider_name: Wego
provider_slug: wego
slug: wego-eligibility
source_date: '2026-11-10'
source_filename: wego-eligibility.yml
source_heading: Eligibility
source_page: https://company.wego.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wego\naid: wego\nurl: https://company.wego.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://company.wego.com/terms-of-service/\n  - https://developers.wego.com/docs/affiliate/terms-of-service\ncountries:\n  served:\n  - EG\n  - IN\n  - PK\n  - SA\n  - AE\n  excluded: []\n  text: 'Users in the following countries will be served by the following Wego entities: Egypt: Wego Travel (under\n    license 730) India: Wego Search Technologies Private Limited Pakistan: Wego Travel & Tourism (Private) Ltd Saudi\n    Arabia: Wego Saudi for Travel and Tourism Services United Arab Emirates: Wego ME\
  \ Travel & Tourism'\nentity_types:\n- type: individual\n  text: You agree that you will use the Services solely for your own personal, non-commercial, lawful purposes\nrestricted_uses:\n- summary: Unlawful, speculative or fraudulent reservations\n  text: not for any purpose that is unlawful or prohibited by these Terms, including without limitation, to make\n    any speculative, false or fraudulent reservation\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Certain cryptocurrency transactions require identity verification (ID upload) as per regulatory requirements,\n    which are beyond Wego’s control\nminimum_age:\n  value: '18'\n  text: You must be a resident of the Kingdom of Saudi Arabia and at least 18 years of age to use STC Pay.\n"
source_yaml_url: https://artifacts.apis.io/wego/eligibility/wego-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Wego's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Travel
- Flights
- Hotels
- Metasearch
- Booking
- Agent-Native
- Tourism
- Search
---
