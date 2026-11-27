---
api_specs:
- filename: carragent-com-agents-api-openapi.yml
  format: yaml
  label: carragent-com Agents API
  slug: carragent-com-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carragent-com/openapi/carragent-com-agents-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Carragent is for business use, not for personal or household use.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sensitive data not to be stored
    text: store data the service is not built for, such as card numbers, government IDs, passwords or detailed health records, in notes or messages
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
name: carragent-com
provenance_date: '2026-11-09'
provider_name: carragent-com
provider_slug: carragent-com
slug: carragent-com-eligibility
source_date: '2026-11-09'
source_filename: carragent-com-eligibility.yml
source_heading: Eligibility
source_page: https://carragent.com/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: carragent-com\naid: carragent-com\nurl: https://carragent.com/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Carragent is for business use, not for personal or household use.\nrestricted_uses:\n- summary: Sensitive data not to be stored\n  text: store data the service is not built for, such as card numbers, government IDs, passwords or detailed health\n    records, in notes or messages\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/carragent-com/eligibility/carragent-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from carragent-com's own page on 2026-11-09.
synthetic: false
tags:
- AI Agents
- Business tools integration
---
