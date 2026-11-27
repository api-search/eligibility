---
api_specs:
- filename: ambermem-com-openapi-generated.yml
  format: yaml
  label: Amber API
  slug: ambermem-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ambermem-com/openapi/_ae-authored/ambermem-com-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old.
    type: individual
  minimum_age:
    text: You must be at least 18 years old.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use Amber, you must have a verified PayPal account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Amber
provenance_date: '2026-11-09'
provider_name: Amber
provider_slug: ambermem-com
slug: ambermem-com-eligibility
source_date: '2026-11-09'
source_filename: ambermem-com-eligibility.yml
source_heading: Eligibility
source_page: https://ambermem.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Amber\naid: ambermem-com\nurl: https://ambermem.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use Amber, you must have a verified PayPal account.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/ambermem-com/eligibility/ambermem-com-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from Amber's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Memory
- Subscription
- MCP
- Personal Data
---
