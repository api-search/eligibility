---
api_specs:
- filename: callforme-tel-account-api-openapi.yml
  format: yaml
  label: CallForMe Account API
  slug: callforme-tel-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callforme-tel/openapi/callforme-tel-account-api-openapi.yml
- filename: callforme-tel-batches-api-openapi.yml
  format: yaml
  label: CallForMe Batches API
  slug: callforme-tel-batches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callforme-tel/openapi/callforme-tel-batches-api-openapi.yml
- filename: callforme-tel-businesses-api-openapi.yml
  format: yaml
  label: CallForMe Businesses API
  slug: callforme-tel-businesses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callforme-tel/openapi/callforme-tel-businesses-api-openapi.yml
- filename: callforme-tel-calls-api-openapi.yml
  format: yaml
  label: CallForMe Calls API
  slug: callforme-tel-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callforme-tel/openapi/callforme-tel-calls-api-openapi.yml
- filename: callforme-tel-pricing-api-openapi.yml
  format: yaml
  label: CallForMe Pricing API
  slug: callforme-tel-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callforme-tel/openapi/callforme-tel-pricing-api-openapi.yml
- filename: callforme-tel-setups-api-openapi.yml
  format: yaml
  label: CallForMe Setups API
  slug: callforme-tel-setups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callforme-tel/openapi/callforme-tel-setups-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No calls to private individuals or emergencies
    text: Calling private individuals, personal cell phones, or anyone who has asked not to be called.
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
name: CallForMe
provenance_date: '2026-11-09'
provider_name: CallForMe
provider_slug: callforme-tel
slug: callforme-tel-eligibility
source_date: '2026-11-09'
source_filename: callforme-tel-eligibility.yml
source_heading: Eligibility
source_page: https://callforme.tel/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CallForMe\naid: callforme-tel\nurl: https://callforme.tel/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No calls to private individuals or emergencies\n  text: Calling private individuals, personal cell phones, or anyone who has asked not to be called.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/callforme-tel/eligibility/callforme-tel-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from CallForMe's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- Voice
- Phone Calls
- Telephony
- MCP
- REST API
---
