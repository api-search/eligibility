---
api_specs:
- filename: supplymaven-com-openapi-generated.yml
  format: yaml
  label: supplymaven-com API
  slug: supplymaven-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/supplymaven-com/openapi/_ae-authored/supplymaven-com-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: SupplyMaven is a business-to-business service not intended for individuals under 18 years of age.
    type: business
  minimum_age:
    text: not intended for individuals under 18 years of age
    value: '18'
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
name: supplymaven-com
provenance_date: '2026-11-10'
provider_name: supplymaven-com
provider_slug: supplymaven-com
slug: supplymaven-com-eligibility
source_date: '2026-11-10'
source_filename: supplymaven-com-eligibility.yml
source_heading: Eligibility
source_page: https://supplymaven.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: supplymaven-com\naid: supplymaven-com\nurl: https://supplymaven.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: SupplyMaven is a business-to-business service not intended for individuals under 18 years of age.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: not intended for individuals under 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/supplymaven-com/eligibility/supplymaven-com-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from supplymaven-com's own page on 2026-11-10.
synthetic: false
tags:
- Supply Chain
- Risk Intelligence
- Data Platform
- Analytics
- Logistics
---
