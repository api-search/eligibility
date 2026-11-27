---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is intended for a special audience over the age of 18 and involved in organized athletics and sports, including athletes, sports teams, coaches, and/or their related entities, administrators, and other affiliated personnel (collectively, "Participants").
    type: other
  minimum_age:
    text: If you are under the age of 18, you may only use the Site with the consent of your parent or legal guardian.
    value: '18'
  restricted_uses:
  - summary: Personal non-commercial use
    text: Unless otherwise specified, the Site is for your personal and non-commercial use.
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
name: Player's Health
provenance_date: '2026-11-10'
provider_name: Player's Health
provider_slug: players-health
slug: players-health-eligibility
source_date: '2026-11-10'
source_filename: players-health-eligibility.yml
source_heading: Eligibility
source_page: https://playershealth.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Player's Health\naid: players-health\nurl: https://playershealth.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: The Site is intended for a special audience over the age of 18 and involved in organized athletics and sports,\n    including athletes, sports teams, coaches, and/or their related entities, administrators, and other affiliated\n    personnel (collectively, \"Participants\").\nrestricted_uses:\n- summary: Personal non-commercial use\n  text: Unless otherwise specified, the Site is for your personal and non-commercial\
  \ use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are under the age of 18, you may only use the Site with the consent of your parent or legal guardian.\n"
source_yaml_url: https://artifacts.apis.io/players-health/eligibility/players-health-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Player's Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Insurance
- Insurtech
- Sports
- Youth Sports
- Athlete Safety
- Risk Management
- Compliance
- Background Screening
---
