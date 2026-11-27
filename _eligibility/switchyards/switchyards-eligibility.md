---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Membership is only available to individuals 18 years of age or older.
    type: individual
  - text: If you are using the Site or any Services on behalf of a company or other legal entity, the term “you” shall also refer to such entity
    type: business
  minimum_age:
    text: Membership is only available to individuals 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: No illegal activity or hate content
    text: No illegal activity in the Work Club or online.
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
name: Switchyards
provenance_date: '2026-11-10'
provider_name: Switchyards
provider_slug: switchyards
slug: switchyards-eligibility
source_date: '2026-11-10'
source_filename: switchyards-eligibility.yml
source_heading: Eligibility
source_page: https://www.switchyards.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Switchyards\naid: switchyards\nurl: https://www.switchyards.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Membership is only available to individuals 18 years of age or older.\n- type: business\n  text: If you are using the Site or any Services on behalf of a company or other legal entity, the term “you” shall\n    also refer to such entity\nrestricted_uses:\n- summary: No illegal activity or hate content\n  text: No illegal activity in the Work Club or online.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: Membership is only available to individuals 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/switchyards/eligibility/switchyards-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Switchyards's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Co-Working
- Workspace
- Membership
- Productivity
- Coffee
---
