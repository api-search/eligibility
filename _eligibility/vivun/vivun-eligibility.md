---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Vivun’s Services are intended for use by businesses and organizations and not for consumer purposes.
    type: business
  minimum_age:
    text: To the extent prohibited by applicable law, the Services are not intended for and should not be used by anyone under the age of sixteen.
    value: '16'
  restricted_uses:
  - summary: Direct competitors barred
    text: You may not access the Site if you are a direct competitor of Vivun, except with Vivun’s express written consent.
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
name: Vivun
provenance_date: '2026-11-10'
provider_name: Vivun
provider_slug: vivun
slug: vivun-eligibility
source_date: '2026-11-10'
source_filename: vivun-eligibility.yml
source_heading: Eligibility
source_page: https://legal.vivun.com/#contract-qdvb9vzdq
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vivun\naid: vivun\nurl: https://legal.vivun.com/#contract-qdvb9vzdq\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Vivun’s Services are intended for use by businesses and organizations and not for consumer purposes.\nrestricted_uses:\n- summary: Direct competitors barred\n  text: You may not access the Site if you are a direct competitor of Vivun, except with Vivun’s express written\n    consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text:\
  \ To the extent prohibited by applicable law, the Services are not intended for and should not be used by\n    anyone under the age of sixteen.\n"
source_yaml_url: https://artifacts.apis.io/vivun/eligibility/vivun-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Vivun's own page on 2026-11-10.
synthetic: false
tags:
- Company
- B2B
- Sales
- Artificial Intelligence
- Presales
- Sales Engineering
- Revenue
- Software-as-a-Service
---
