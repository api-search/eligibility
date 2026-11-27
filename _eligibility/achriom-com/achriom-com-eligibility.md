---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Use the App only for personal, non-commercial purposes
    type: individual
  minimum_age:
    text: You must be at least 13 years old to use Achriom.
    value: '13'
  restricted_uses:
  - summary: Personal, non-commercial only
    text: Use the App only for personal, non-commercial purposes
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
name: Achriom
provenance_date: '2026-11-09'
provider_name: Achriom
provider_slug: achriom-com
slug: achriom-com-eligibility
source_date: '2026-11-09'
source_filename: achriom-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.achriom.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Achriom\naid: achriom-com\nurl: https://www.achriom.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Use the App only for personal, non-commercial purposes\nrestricted_uses:\n- summary: Personal, non-commercial only\n  text: Use the App only for personal, non-commercial purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use Achriom.\n"
source_yaml_url: https://artifacts.apis.io/achriom-com/eligibility/achriom-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Achriom's own page on 2026-11-09.
synthetic: false
tags:
- Media
- Entertainment
- Library
- Discovery
- Community
---
