---
api_specs:
- filename: cityoftrees-house-agent-api-openapi.yml
  format: yaml
  label: City of Trees House Agent API
  slug: cityoftrees-house-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cityoftrees-house/openapi/cityoftrees-house-agent-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: The primary renter must be at least 25 years old; other registered guests may be younger.
    value: '25'
  restricted_uses:
  - summary: Smoking and vaping
    text: Smoking and vaping are prohibited everywhere on the property, indoors and outdoors.
  - summary: Occupancy limit
    text: Maximum occupancy is 10 guests.
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
name: City of Trees House
provenance_date: '2026-11-09'
provider_name: City of Trees House
provider_slug: cityoftrees-house
slug: cityoftrees-house-eligibility
source_date: '2026-11-09'
source_filename: cityoftrees-house-eligibility.yml
source_heading: Eligibility
source_page: https://cityoftrees.house/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: City of Trees House\naid: cityoftrees-house\nurl: https://cityoftrees.house/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Smoking and vaping\n  text: Smoking and vaping are prohibited everywhere on the property, indoors and outdoors.\n- summary: Occupancy limit\n  text: Maximum occupancy is 10 guests.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '25'\n  text: The primary renter must be at least 25 years old; other registered guests may be younger.\n"
source_yaml_url: https://artifacts.apis.io/cityoftrees-house/eligibility/cityoftrees-house-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from City of Trees House's own page on 2026-11-09.
synthetic: false
tags:
- Vacation Rentals
- West Sacramento
- Family Run
- Hospitality
- Vacation Home
---
