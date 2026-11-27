---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must provide a valid email address and be old enough to consent to receive email where you live.
    type: individual
  minimum_age:
    text: be old enough to consent to receive email where you live
    value: null
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
name: AI Daily Brew
provenance_date: '2026-11-09'
provider_name: AI Daily Brew
provider_slug: aidailybrew-com
slug: aidailybrew-com-eligibility
source_date: '2026-11-09'
source_filename: aidailybrew-com-eligibility.yml
source_heading: Eligibility
source_page: https://aidailybrew.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AI Daily Brew\naid: aidailybrew-com\nurl: https://aidailybrew.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must provide a valid email address and be old enough to consent to receive email where you live.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: be old enough to consent to receive email where you live\n"
source_yaml_url: https://artifacts.apis.io/aidailybrew-com/eligibility/aidailybrew-com-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from AI Daily Brew's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Newsletters
- Daily
- Builders
- Technology
---
