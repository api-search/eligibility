---
api_specs:
- filename: orange-health-orders-api-openapi.yml
  format: yaml
  label: Orange Health Orders API
  slug: orange-health-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orange-health/openapi/orange-health-orders-api-openapi.yml
- filename: orange-health-results-api-openapi.yml
  format: yaml
  label: Orange Health Results API
  slug: orange-health-results-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orange-health/openapi/orange-health-results-api-openapi.yml
- filename: orange-health-serviceability-api-openapi.yml
  format: yaml
  label: Orange Health Serviceability API
  slug: orange-health-serviceability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orange-health/openapi/orange-health-serviceability-api-openapi.yml
- filename: orange-health-orange-health-partner-api-api-openapi.yml
  format: yaml
  label: Orange Health Orange Health Partner API
  slug: orange-health-orange-health-partner-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orange-health/openapi/orange-health-orange-health-partner-api-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: The Application and the Services are designed to be used within India. Please refrain from using the Application or receiving or rendering any Services through use of the Application outside of India.
  entity_types:
  - text: a natural individual who is 18 (eighteen) years of age or older to use the Application or the Services
    type: individual
  - text: You must be a validly constituted legal entity
    type: business
  minimum_age:
    text: a natural individual who is 18 (eighteen) years of age or older
    value: '18'
  restricted_uses:
  - summary: Illegal or offensive content
    text: You will not use the Application or the Services in a manner or for any purpose that is illegal, discriminatory, immoral or offensive.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Orange Health
provenance_date: '2026-11-10'
provider_name: Orange Health
provider_slug: orange-health
slug: orange-health-eligibility
source_date: '2026-11-10'
source_filename: orange-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.orangehealth.in/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Orange Health\naid: orange-health\nurl: https://www.orangehealth.in/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: The Application and the Services are designed to be used within India. Please refrain from using the Application\n    or receiving or rendering any Services through use of the Application outside of India.\nentity_types:\n- type: individual\n  text: a natural individual who is 18 (eighteen) years of age or older to use the Application or the Services\n- type: business\n  text: You must be a validly constituted legal entity\nrestricted_uses:\n- summary: Illegal\
  \ or offensive content\n  text: You will not use the Application or the Services in a manner or for any purpose that is illegal, discriminatory,\n    immoral or offensive.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: a natural individual who is 18 (eighteen) years of age or older\n"
source_yaml_url: https://artifacts.apis.io/orange-health/eligibility/orange-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Orange Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Mobile
- Healthcare
- Diagnostics
- Lab Testing
- Home Collection
- Webhook
- India
---
