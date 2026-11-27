---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: Customer will not permit any User to access or use any Service or Content in a U.S.-embargoed country or region (currently Cuba, Iran, North Korea, Sudan, Syria, or Crimea)
  entity_types:
  - text: in the case of an individual accepting this Agreement on behalf of a company or other legal entity
    type: business
  - text: in the case of an individual accepting this Agreement on his or her own behalf, such individual
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export-restricted access
    text: or in violation of any U.S. export law or regulation
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Atolio
provenance_date: '2026-11-09'
provider_name: Atolio
provider_slug: atolio
slug: atolio-eligibility
source_date: '2026-11-09'
source_filename: atolio-eligibility.yml
source_heading: Eligibility
source_page: https://www.atolio.com/msa
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Atolio\naid: atolio\nurl: https://www.atolio.com/msa\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: Customer will not permit any User to access or use any Service or Content in a U.S.-embargoed country or\n    region (currently Cuba, Iran, North Korea, Sudan, Syria, or Crimea)\nentity_types:\n- type: business\n  text: in the case of an individual accepting this Agreement on behalf of a company or other legal entity\n- type: individual\n  text: in the case of an individual accepting this Agreement on his or her own behalf, such individual\nrestricted_uses:\n\
  - summary: Export-restricted access\n  text: or in violation of any U.S. export law or regulation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/atolio/eligibility/atolio-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Atolio's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Enterprise Search
- Data Security
- Integration
- Software-as-a-Service
---
