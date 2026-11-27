---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Any natural person with full legal capacity to enter into a contract
    type: individual
  - text: Any legal entity acting through a duly authorized representative with authority to bind such entity to the Terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Motorcycle on-road use only
    text: The Device is a Head-Mounted Display (HMD) intended for use on motorcycle helmets for on-road use only
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
name: EyeLights
provenance_date: '2026-11-09'
provider_name: EyeLights
provider_slug: eyelights
slug: eyelights-eligibility
source_date: '2026-11-09'
source_filename: eyelights-eligibility.yml
source_heading: Eligibility
source_page: https://eye-lights.com/en/pages/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EyeLights\naid: eyelights\nurl: https://eye-lights.com/en/pages/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Any natural person with full legal capacity to enter into a contract\n- type: business\n  text: Any legal entity acting through a duly authorized representative with authority to bind such entity to the\n    Terms.\nrestricted_uses:\n- summary: Motorcycle on-road use only\n  text: The Device is a Head-Mounted Display (HMD) intended for use on motorcycle helmets for on-road use only\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/eyelights/eligibility/eyelights-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from EyeLights's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Augmented Reality
- Head-Up Display
- Wearables
- Hardware
- Motorcycles
- Aviation
- Navigation
- Consumer Electronics
- Techstars
---
