---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: USER MUST BE AT LEAST 18 YEARS OLD TO ACCESS AND USE THE SITE.
    type: individual
  minimum_age:
    text: USER MUST BE AT LEAST 18 YEARS OLD TO ACCESS AND USE THE SITE.
    value: '18'
  restricted_uses:
  - summary: Informational use only, not medical advice
    text: THE CONTENT ON THE SITE SHOULD NOT BE CONSIDERED MEDICAL ADVICE.
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
name: Hopscotch
provenance_date: '2026-11-09'
provider_name: Hopscotch
provider_slug: hopscotch
slug: hopscotch-eligibility
source_date: '2026-11-09'
source_filename: hopscotch-eligibility.yml
source_heading: Eligibility
source_page: https://www.hellohopscotch.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hopscotch\naid: hopscotch\nurl: https://www.hellohopscotch.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: USER MUST BE AT LEAST 18 YEARS OLD TO ACCESS AND USE THE SITE.\nrestricted_uses:\n- summary: Informational use only, not medical advice\n  text: THE CONTENT ON THE SITE SHOULD NOT BE CONSIDERED MEDICAL ADVICE.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: USER MUST BE AT LEAST 18 YEARS OLD TO ACCESS AND USE THE SITE.\n"
source_yaml_url: https://artifacts.apis.io/hopscotch/eligibility/hopscotch-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Hopscotch's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Primary Care
- Medicare
- Value-Based Care
- Rural Health
- Senior Care
---
