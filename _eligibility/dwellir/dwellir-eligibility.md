---
api_specs:
- filename: dwellir-openapi-generated.yml
  format: yaml
  label: Dwellir API
  slug: dwellir-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwellir/openapi/_ae-authored/dwellir-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To use our Services, you must be at least 18 years old and have the legal capacity to enter into binding agreements.
    type: individual
  - text: Each individual or entity may maintain only one account.
    type: business
  minimum_age:
    text: you must be at least 18 years old and have the legal capacity to enter into binding agreements
    value: '18'
  restricted_uses:
  - summary: Illegal activities
    text: You agree to use our Services only for lawful purposes and in accordance with these Terms.
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
name: Dwellir
provenance_date: '2026-11-09'
provider_name: Dwellir
provider_slug: dwellir
slug: dwellir-eligibility
source_date: '2026-11-09'
source_filename: dwellir-eligibility.yml
source_heading: Eligibility
source_page: https://www.dwellir.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dwellir\naid: dwellir\nurl: https://www.dwellir.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To use our Services, you must be at least 18 years old and have the legal capacity to enter into binding\n    agreements.\n- type: business\n  text: Each individual or entity may maintain only one account.\nrestricted_uses:\n- summary: Illegal activities\n  text: You agree to use our Services only for lawful purposes and in accordance with these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years old and have the legal capacity to enter into binding agreements\n"
source_yaml_url: https://artifacts.apis.io/dwellir/eligibility/dwellir-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Dwellir's own page on 2026-11-09.
synthetic: false
tags:
- Blockchain
- Infrastructure
- RPC
- Web3
---
