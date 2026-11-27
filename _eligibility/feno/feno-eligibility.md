---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This Platform is offered and available to users who are 18 years of age or older.
    type: individual
  minimum_age:
    text: This Platform is offered and available to users who are 18 years of age or older.
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
name: Feno
provenance_date: '2026-11-09'
provider_name: Feno
provider_slug: feno
slug: feno-eligibility
source_date: '2026-11-09'
source_filename: feno-eligibility.yml
source_heading: Eligibility
source_page: https://feno.co/pages/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Feno\naid: feno\nurl: https://feno.co/pages/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: This Platform is offered and available to users who are 18 years of age or older.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: This Platform is offered and available to users who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/feno/eligibility/feno-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Feno's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Oral Care
- Health Tech
- Smartbrush
- Artificial Intelligence
- Consumer Electronics
---
