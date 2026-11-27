---
api_specs:
- filename: awning-help-openapi-generated.yml
  format: yaml
  label: Awning API
  slug: awning-help-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awning-help/openapi/_ae-authored/awning-help-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: List only a business you run or are authorised to represent
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Every business is reviewed before it goes live.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Awning
provenance_date: '2026-11-09'
provider_name: Awning
provider_slug: awning-help
slug: awning-help-eligibility
source_date: '2026-11-09'
source_filename: awning-help-eligibility.yml
source_heading: Eligibility
source_page: https://awning.help/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Awning\naid: awning-help\nurl: https://awning.help/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: List only a business you run or are authorised to represent\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Every business is reviewed before it goes live.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/awning-help/eligibility/awning-help-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from Awning's own page on 2026-11-09.
synthetic: false
tags:
- Booking
- Local Services
- AI Assistant
- Marketplace
- Scheduling
---
