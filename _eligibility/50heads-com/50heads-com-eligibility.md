---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use 50heads for an organization, you accept them for that organization and confirm you're allowed to.
    type: business
  - text: If you're a consumer living elsewhere in the UK or the EU, you can also bring proceedings where you live.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Acceptable use policy breaches
    text: We may suspend or close an account that breaks these terms, puts heads at risk, or is used for fraud.
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
name: 50heads
provenance_date: '2026-11-09'
provider_name: 50heads
provider_slug: 50heads-com
slug: 50heads-com-eligibility
source_date: '2026-11-09'
source_filename: 50heads-com-eligibility.yml
source_heading: Eligibility
source_page: https://50heads.com/en-us/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 50heads\naid: 50heads-com\nurl: https://50heads.com/en-us/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use 50heads for an organization, you accept them for that organization and confirm you're allowed\n    to.\n- type: individual\n  text: If you're a consumer living elsewhere in the UK or the EU, you can also bring proceedings where you live.\nrestricted_uses:\n- summary: Acceptable use policy breaches\n  text: We may suspend or close an account that breaks these terms, puts heads at risk, or is used for fraud.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/50heads-com/eligibility/50heads-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from 50heads's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Verification
- Surveys
- Platform
---
