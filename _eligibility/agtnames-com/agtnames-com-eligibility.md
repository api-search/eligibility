---
api_specs:
- filename: agtnames-com-openapi-generated.yml
  format: yaml
  label: AGT Names API
  slug: agtnames-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agtnames-com/openapi/_ae-authored/agtnames-com-openapi-generated.yml
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
  - summary: Resale or squatting
    text: Register names for the purpose of resale or domain squatting.
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
name: AGT Names
provenance_date: '2026-11-09'
provider_name: AGT Names
provider_slug: agtnames-com
slug: agtnames-com-eligibility
source_date: '2026-11-09'
source_filename: agtnames-com-eligibility.yml
source_heading: Eligibility
source_page: https://agtnames.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AGT Names\naid: agtnames-com\nurl: https://agtnames.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Resale or squatting\n  text: Register names for the purpose of resale or domain squatting.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agtnames-com/eligibility/agtnames-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from AGT Names's own page on 2026-11-09.
synthetic: false
tags:
- Blockchain
- Identity
- Artificial Intelligence
- Decentralized
- Web3
---
