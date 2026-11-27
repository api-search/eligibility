---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Codes by email, 80+ countries.
  entity_types:
  - text: public offer to any capable adult individual or legal entity
    type: individual
  - text: public offer to any capable adult individual or legal entity
    type: business
  minimum_age:
    text: are 18 years of age or older (or have legal guardian consent)
    value: '18'
  restricted_uses:
  - summary: Regional restrictions
    text: Regional restrictions are essential contract conditions.
  - summary: Personal use only
    text: Digital goods are exclusively for personal use.
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
name: BlinkCodes
provenance_date: '2026-11-09'
provider_name: BlinkCodes
provider_slug: blinkcodes-com
slug: blinkcodes-com-eligibility
source_date: '2026-11-09'
source_filename: blinkcodes-com-eligibility.yml
source_heading: Eligibility
source_page: https://blinkcodes.com/en/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BlinkCodes\naid: blinkcodes-com\nurl: https://blinkcodes.com/en/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Codes by email, 80+ countries.\nentity_types:\n- type: individual\n  text: public offer to any capable adult individual or legal entity\n- type: business\n  text: public offer to any capable adult individual or legal entity\nrestricted_uses:\n- summary: Regional restrictions\n  text: Regional restrictions are essential contract conditions.\n- summary: Personal use only\n  text: Digital goods are exclusively for personal use.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: are 18 years of age or older (or have legal guardian consent)\n"
source_yaml_url: https://artifacts.apis.io/blinkcodes-com/eligibility/blinkcodes-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from BlinkCodes's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Gift Cards
- eSIM
- Virtual Numbers
---
