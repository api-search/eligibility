---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You need to be old enough to enter a binding contract where you live.
    type: individual
  minimum_age:
    text: You need to be old enough to enter a binding contract where you live.
    value: null
  restricted_uses:
  - summary: Illegal or harmful use
    text: Do not use Actually Asked for anything illegal, or to harm, harass or deceive anyone.
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
name: Actually Asked
provenance_date: '2026-11-09'
provider_name: Actually Asked
provider_slug: actuallyasked-com
slug: actuallyasked-com-eligibility
source_date: '2026-11-09'
source_filename: actuallyasked-com-eligibility.yml
source_heading: Eligibility
source_page: https://actuallyasked.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Actually Asked\naid: actuallyasked-com\nurl: https://actuallyasked.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You need to be old enough to enter a binding contract where you live.\nrestricted_uses:\n- summary: Illegal or harmful use\n  text: Do not use Actually Asked for anything illegal, or to harm, harass or deceive anyone.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You need to be old enough to enter a binding contract where you live.\n"
source_yaml_url: https://artifacts.apis.io/actuallyasked-com/eligibility/actuallyasked-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Actually Asked's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- FAQ
- Shopify
- Integration
- Software-as-a-Service
- Company
---
