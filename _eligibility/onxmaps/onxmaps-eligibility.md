---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you are not a United States resident and you are accessing the Services from outside the United States, you agree to transfer certain information outside your home country to us
  entity_types:
  - text: 'You represent and warrant that you are: (i) over eighteen years of age or the age of majority in your jurisdiction, whichever is greater'
    type: individual
  minimum_age:
    text: over eighteen years of age or the age of majority in your jurisdiction, whichever is greater
    value: '18'
  restricted_uses:
  - summary: Non-commercial use only
    text: You agree to use the Service for your personal, non-commercial use only (unless you have an onX for Business license agreement with us).
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
name: OnXMaps
provenance_date: '2026-11-10'
provider_name: OnXMaps
provider_slug: onxmaps
slug: onxmaps-eligibility
source_date: '2026-11-10'
source_filename: onxmaps-eligibility.yml
source_heading: Eligibility
source_page: https://www.onxmaps.com/tou
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OnXMaps\naid: onxmaps\nurl: https://www.onxmaps.com/tou\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you are not a United States resident and you are accessing the Services from outside the United States,\n    you agree to transfer certain information outside your home country to us\nentity_types:\n- type: individual\n  text: 'You represent and warrant that you are: (i) over eighteen years of age or the age of majority in your jurisdiction,\n    whichever is greater'\nrestricted_uses:\n- summary: Non-commercial use only\n  text: You agree to use the Service for your personal,\
  \ non-commercial use only (unless you have an onX for Business\n    license agreement with us).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: over eighteen years of age or the age of majority in your jurisdiction, whichever is greater\n"
source_yaml_url: https://artifacts.apis.io/onxmaps/eligibility/onxmaps-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from OnXMaps's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Mapping
- GPS
- Navigation
- Outdoor Recreation
- Location
- Geospatial
---
