---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Our Services are provided for your personal, non-commercial use only.
    type: individual
  minimum_age:
    text: IF YOU ARE UNDER THE AGE OF EIGHTEEN (18), THEN YOU ARE NOT PERMITTED TO REGISTER AS A USER
    value: '18'
  restricted_uses:
  - summary: Non-commercial use only
    text: Our Services are provided for your personal, non-commercial use only.
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
name: Cintas
provenance_date: '2026-11-09'
provider_name: Cintas
provider_slug: cintas
slug: cintas-eligibility
source_date: '2026-11-09'
source_filename: cintas-eligibility.yml
source_heading: Eligibility
source_page: https://www.cintas.com/legal/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cintas\naid: cintas\nurl: https://www.cintas.com/legal/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Our Services are provided for your personal, non-commercial use only.\nrestricted_uses:\n- summary: Non-commercial use only\n  text: Our Services are provided for your personal, non-commercial use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: IF YOU ARE UNDER THE AGE OF EIGHTEEN (18), THEN YOU ARE NOT PERMITTED TO REGISTER AS A USER\n"
source_yaml_url: https://artifacts.apis.io/cintas/eligibility/cintas-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Cintas's own page on 2026-11-09.
synthetic: false
tags:
- Facility Services
- First Aid
- Fortune 500
- Safety
- Uniforms
---
