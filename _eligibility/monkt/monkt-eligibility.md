---
api_specs:
- filename: monkt-openapi-generated.yml
  format: yaml
  label: Monkt API
  slug: monkt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monkt/openapi/_ae-authored/monkt-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'We reserve the right to: Limit service availability by region'
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal content or purposes
    text: Processing of illegal content
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
name: Monkt
provenance_date: '2026-11-10'
provider_name: Monkt
provider_slug: monkt
slug: monkt-eligibility
source_date: '2026-11-10'
source_filename: monkt-eligibility.yml
source_heading: Eligibility
source_page: https://monkt.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Monkt\naid: monkt\nurl: https://monkt.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'We reserve the right to: Limit service availability by region'\nentity_types: []\nrestricted_uses:\n- summary: Illegal content or purposes\n  text: Processing of illegal content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/monkt/eligibility/monkt-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Monkt's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Document Processing
- Automation
---
