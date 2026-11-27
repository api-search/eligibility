---
api_specs:
- filename: crossandcovenant-co-openapi.yaml
  format: yaml
  label: Cross + Covenant Agent API
  slug: agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crossandcovenant-co/openapi/_original/crossandcovenant-co-openapi.yaml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old, or the age of majority in your jurisdiction, to make a purchase.
    type: individual
  minimum_age:
    text: You must be at least 18 years old, or the age of majority in your jurisdiction, to make a purchase.
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
name: crossandcovenant-co
provenance_date: '2026-11-09'
provider_name: crossandcovenant-co
provider_slug: crossandcovenant-co
slug: crossandcovenant-co-eligibility
source_date: '2026-11-09'
source_filename: crossandcovenant-co-eligibility.yml
source_heading: Eligibility
source_page: https://crossandcovenant.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: crossandcovenant-co\naid: crossandcovenant-co\nurl: https://crossandcovenant.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old, or the age of majority in your jurisdiction, to make a purchase.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age of majority in your jurisdiction, to make a purchase.\n"
source_yaml_url: https://artifacts.apis.io/crossandcovenant-co/eligibility/crossandcovenant-co-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from crossandcovenant-co's own page on 2026-11-09.
synthetic: false
tags:
- Apparel
- Christian
- E-Commerce
- Faith
- Charity
---
