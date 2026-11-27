---
api_specs:
- filename: shotkit-net-openapi-generated.yml
  format: yaml
  label: shotkit-net API
  slug: shotkit-net-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shotkit-net/openapi/_ae-authored/shotkit-net-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use it on behalf of a company, you agree for that company.
    type: business
  minimum_age:
    text: You must be old enough to enter a contract where you live.
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
name: shotkit-net
provenance_date: '2026-11-10'
provider_name: shotkit-net
provider_slug: shotkit-net
slug: shotkit-net-eligibility
source_date: '2026-11-10'
source_filename: shotkit-net-eligibility.yml
source_heading: Eligibility
source_page: https://shotkit.net/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: shotkit-net\naid: shotkit-net\nurl: https://shotkit.net/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use it on behalf of a company, you agree for that company.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You must be old enough to enter a contract where you live.\n"
source_yaml_url: https://artifacts.apis.io/shotkit-net/eligibility/shotkit-net-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from shotkit-net's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Screenshots
- Web
- Automation
---
