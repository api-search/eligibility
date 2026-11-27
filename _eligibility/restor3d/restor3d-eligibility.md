---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You live in the United States and in a state or territory where the Services are available. We provide the Services for use only by persons located in the United States.
  minimum_age:
    text: You are at least 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Not medical advice
    text: NEITHER RESTOR3D NOR THE SERVICES OFFERS MEDICAL ADVICE.
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
name: restor3d
provenance_date: '2026-11-10'
provider_name: restor3d
provider_slug: restor3d
slug: restor3d-eligibility
source_date: '2026-11-10'
source_filename: restor3d-eligibility.yml
source_heading: Eligibility
source_page: https://www.restor3d.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: restor3d\naid: restor3d\nurl: https://www.restor3d.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You live in the United States and in a state or territory where the Services are available. We provide the\n    Services for use only by persons located in the United States.\nentity_types: []\nrestricted_uses:\n- summary: Not medical advice\n  text: NEITHER RESTOR3D NOR THE SERVICES OFFERS MEDICAL ADVICE.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least 18 years of\
  \ age or older.\n"
source_yaml_url: https://artifacts.apis.io/restor3d/eligibility/restor3d-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from restor3d's own page on 2026-11-10.
synthetic: false
tags:
- Medical Devices
- Health
- Orthopedics
- 3D Printing
- Implants
- Surgery
- Artificial Intelligence
- Manufacturing
- Company
---
