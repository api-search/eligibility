---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This Website is offered and available to users who are 18 years of age or older and reside in the United States or any of its territories or possessions.
  entity_types:
  - text: This Website is offered and available to users who are 18 years of age or older and reside in the United States or any of its territories or possessions.
    type: individual
  minimum_age:
    text: users who are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: You may use the Website only for lawful purposes and in accordance with these Terms of Use.
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
name: Branch Energy
provenance_date: '2026-11-09'
provider_name: Branch Energy
provider_slug: branch-energy
slug: branch-energy-eligibility
source_date: '2026-11-09'
source_filename: branch-energy-eligibility.yml
source_heading: Eligibility
source_page: https://branchenergy.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Branch Energy\naid: branch-energy\nurl: https://branchenergy.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This Website is offered and available to users who are 18 years of age or older and reside in the United\n    States or any of its territories or possessions.\nentity_types:\n- type: individual\n  text: This Website is offered and available to users who are 18 years of age or older and reside in the United\n    States or any of its territories or possessions.\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You may use the Website only for lawful\
  \ purposes and in accordance with these Terms of Use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: users who are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/branch-energy/eligibility/branch-energy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Branch Energy's own page on 2026-11-09.
synthetic: false
tags:
- Energy
- Electricity
- Battery Storage
- Texas
- Retail
---
