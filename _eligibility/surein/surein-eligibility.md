---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: adult natural persons
    type: individual
  - text: personal partnerships, legal entities
    type: business
  minimum_age:
    text: adult natural persons
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
name: SureIn
provenance_date: '2026-11-10'
provider_name: SureIn
provider_slug: surein
slug: surein-eligibility
source_date: '2026-11-10'
source_filename: surein-eligibility.yml
source_heading: Eligibility
source_page: https://surein.de/en/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SureIn\naid: surein\nurl: https://surein.de/en/legal/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: adult natural persons\n- type: business\n  text: personal partnerships, legal entities\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: adult natural persons\n"
source_yaml_url: https://artifacts.apis.io/surein/eligibility/surein-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from SureIn's own page on 2026-11-10.
synthetic: false
tags:
- Insurance
- Commercial
- Risk Management
- Germany
- B2B
---
