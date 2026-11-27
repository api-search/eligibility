---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: the United States of America, including Washington, D.C. and all U.S. territories and possessions, but excludes Puerto Rico
  entity_types:
  - text: means all veterinary hospitals and clinics that are owned by or affiliated with Client.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Controlled substances
    text: Controlled Substances are sold exclusively to valid DEA registration holders.
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
name: Covetrus
provenance_date: '2026-11-09'
provider_name: Covetrus
provider_slug: covetrus
slug: covetrus-eligibility
source_date: '2026-11-09'
source_filename: covetrus-eligibility.yml
source_heading: Eligibility
source_page: https://covetrus.com/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Covetrus\naid: covetrus\nurl: https://covetrus.com/legal/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: the United States of America, including Washington, D.C. and all U.S. territories and possessions, but excludes\n    Puerto Rico\nentity_types:\n- type: business\n  text: means all veterinary hospitals and clinics that are owned by or affiliated with Client.\nrestricted_uses:\n- summary: Controlled substances\n  text: Controlled Substances are sold exclusively to valid DEA registration holders.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/covetrus/eligibility/covetrus-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Covetrus's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Veterinary
- Software
- Pharmacy
- Client Communication
---
