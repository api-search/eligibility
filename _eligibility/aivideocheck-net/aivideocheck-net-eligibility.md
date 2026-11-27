---
api_specs:
- filename: aivideocheck-net-openapi-generated.yml
  format: yaml
  label: AI Video Check API
  slug: aivideocheck-net-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aivideocheck-net/openapi/_ae-authored/aivideocheck-net-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is intended for users aged 18 and older.
    type: individual
  minimum_age:
    text: The Service is intended for users aged 18 and older.
    value: '18'
  restricted_uses:
  - summary: No sole basis for decisions with legal effect
    text: you must not use a result as the sole basis for a decision that has a legal or similarly significant effect on a person
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
name: AI Video Check
provenance_date: '2026-11-09'
provider_name: AI Video Check
provider_slug: aivideocheck-net
slug: aivideocheck-net-eligibility
source_date: '2026-11-09'
source_filename: aivideocheck-net-eligibility.yml
source_heading: Eligibility
source_page: https://www.aivideocheck.net/en/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AI Video Check\naid: aivideocheck-net\nurl: https://www.aivideocheck.net/en/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Service is intended for users aged 18 and older.\nrestricted_uses:\n- summary: No sole basis for decisions with legal effect\n  text: you must not use a result as the sole basis for a decision that has a legal or similarly significant effect\n    on a person\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Service is intended\
  \ for users aged 18 and older.\n"
source_yaml_url: https://artifacts.apis.io/aivideocheck-net/eligibility/aivideocheck-net-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AI Video Check's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Video
- Detection
- Ukrainian
- Services
---
