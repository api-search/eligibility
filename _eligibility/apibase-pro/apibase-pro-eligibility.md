---
api_specs:
- filename: apibase-pro-tools-api-openapi.yml
  format: yaml
  label: APIbase Tools API
  slug: apibase-pro-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apibase-pro/openapi/apibase-pro-tools-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: You may not use APIbase if you are located in, or are a resident or national of, Cuba, Iran, North Korea, Syria, or the Crimea, Donetsk or Luhansk regions
  entity_types:
  - text: If you are using the Service on behalf of an organization, you represent that you have authority to bind that organization.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited platform content categories
    text: The following activities are strictly prohibited. Violations result in immediate account suspension and may be reported to law enforcement.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: APIbase
provenance_date: '2026-11-09'
provider_name: APIbase
provider_slug: apibase-pro
slug: apibase-pro-eligibility
source_date: '2026-11-09'
source_filename: apibase-pro-eligibility.yml
source_heading: Eligibility
source_page: https://apibase.pro/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: APIbase\naid: apibase-pro\nurl: https://apibase.pro/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: You may not use APIbase if you are located in, or are a resident or national of, Cuba, Iran, North Korea,\n    Syria, or the Crimea, Donetsk or Luhansk regions\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent that you have authority to bind\n    that organization.\nrestricted_uses:\n- summary: Prohibited platform content categories\n  text: The following activities are strictly prohibited.\
  \ Violations result in immediate account suspension and\n    may be reported to law enforcement.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/apibase-pro/eligibility/apibase-pro-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from APIbase's own page on 2026-11-09.
synthetic: false
tags:
- Gateways
- Artificial Intelligence
- MCP
- Payments
---
