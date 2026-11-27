---
api_specs:
- filename: candor-money-conversations-api-openapi.yml
  format: yaml
  label: Candor Finance Conversations API
  slug: candor-money-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/candor-money/openapi/candor-money-conversations-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use Candor only if you are at least 18 years old, are able to form a binding agreement, and are using the service for personal, family, or household financial context unless we approve another use in writing.
    type: individual
  minimum_age:
    text: You may use Candor only if you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Regulated decisions about others
    text: use Candor output to make eligibility, credit, insurance, employment, housing, or similar regulated decisions about another person
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
name: Candor Finance
provenance_date: '2026-11-09'
provider_name: Candor Finance
provider_slug: candor-money
slug: candor-money-eligibility
source_date: '2026-11-09'
source_filename: candor-money-eligibility.yml
source_heading: Eligibility
source_page: https://candor.money/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Candor Finance\naid: candor-money\nurl: https://candor.money/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use Candor only if you are at least 18 years old, are able to form a binding agreement, and are\n    using the service for personal, family, or household financial context unless we approve another use in writing.\nrestricted_uses:\n- summary: Regulated decisions about others\n  text: use Candor output to make eligibility, credit, insurance, employment, housing, or similar regulated decisions\n    about another\
  \ person\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may use Candor only if you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/candor-money/eligibility/candor-money-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Candor Finance's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Artificial Intelligence
- Personal Finance
- Budgeting
---
