---
api_specs:
- filename: builtonrails-com-openapi-generated.yml
  format: yaml
  label: BuiltOnRails API
  slug: builtonrails-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/builtonrails-com/openapi/_ae-authored/builtonrails-com-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be old enough to enter a contract where you live.
    type: individual
  minimum_age:
    text: You must be old enough to enter a contract where you live.
    value: null
  restricted_uses:
  - summary: No fake or impersonated accounts
    text: Do not create accounts for other people or impersonate anyone.
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
name: BuiltOnRails
provenance_date: '2026-11-09'
provider_name: BuiltOnRails
provider_slug: builtonrails-com
slug: builtonrails-com-eligibility
source_date: '2026-11-09'
source_filename: builtonrails-com-eligibility.yml
source_heading: Eligibility
source_page: https://builtonrails.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BuiltOnRails\naid: builtonrails-com\nurl: https://builtonrails.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be old enough to enter a contract where you live.\nrestricted_uses:\n- summary: No fake or impersonated accounts\n  text: Do not create accounts for other people or impersonate anyone.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You must be old enough to enter a contract where you live.\n"
source_yaml_url: https://artifacts.apis.io/builtonrails-com/eligibility/builtonrails-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from BuiltOnRails's own page on 2026-11-09.
synthetic: false
tags:
- Ruby on Rails
- Stack Data
---
