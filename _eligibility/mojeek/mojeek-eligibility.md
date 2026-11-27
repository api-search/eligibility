---
api_specs:
- filename: mojeek-openapi-generated.yml
  format: yaml
  label: Mojeek API
  slug: mojeek-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mojeek/openapi/_ae-authored/mojeek-openapi-generated.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'You/Your: individual or entity using Our Services.'
    type: other
  minimum_age:
    text: null
    value: null
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
name: Mojeek
provenance_date: '2026-11-10'
provider_name: Mojeek
provider_slug: mojeek
slug: mojeek-eligibility
source_date: '2026-11-10'
source_filename: mojeek-eligibility.yml
source_heading: Eligibility
source_page: https://www.mojeek.com/about/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mojeek\naid: mojeek\nurl: https://www.mojeek.com/about/terms.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: 'You/Your: individual or entity using Our Services.'\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mojeek/eligibility/mojeek-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Mojeek's own page on 2026-11-10.
synthetic: false
tags:
- Search
- Privacy
- Open Source
- Community
---
