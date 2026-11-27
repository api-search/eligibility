---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service may not be available in some countries and may be provided only in selected languages.
  entity_types:
  - text: for Your own private non-commercial purposes strictly in accordance with the Terms
    type: individual
  minimum_age:
    text: To use the Service, You must be at least sixteen (16) years of age.
    value: '16'
  restricted_uses:
  - summary: Betting or prize activities
    text: use the Service for betting or any similar activity in which prizes or rewards can be won (directly or indirectly)
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
name: Suunto
provenance_date: '2026-11-10'
provider_name: Suunto
provider_slug: suunto
slug: suunto-eligibility
source_date: '2026-11-10'
source_filename: suunto-eligibility.yml
source_heading: Eligibility
source_page: https://www.suunto.com/Terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Suunto\naid: suunto\nurl: https://www.suunto.com/Terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Service may not be available in some countries and may be provided only in selected languages.\nentity_types:\n- type: individual\n  text: for Your own private non-commercial purposes strictly in accordance with the Terms\nrestricted_uses:\n- summary: Betting or prize activities\n  text: use the Service for betting or any similar activity in which prizes or rewards can be won (directly or indirectly)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '16'\n  text: To use the Service, You must be at least sixteen (16) years of age.\n"
source_yaml_url: https://artifacts.apis.io/suunto/eligibility/suunto-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Suunto's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sports
- Wearables
- Outdoor
- Navigation
---
