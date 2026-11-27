---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By using our Services, you represent and warrant that you (a) are 18 years of age or older
    type: individual
  minimum_age:
    text: you (a) are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: No offering coaching from multiple accounts
    text: (c) will not offer coaching services from more than one CoachUp account without our express permission
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
name: Coachup
provenance_date: '2026-11-09'
provider_name: Coachup
provider_slug: coachup
slug: coachup-eligibility
source_date: '2026-11-09'
source_filename: coachup-eligibility.yml
source_heading: Eligibility
source_page: https://www.coachup.com/terms_of_service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coachup\naid: coachup\nurl: https://www.coachup.com/terms_of_service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By using our Services, you represent and warrant that you (a) are 18 years of age or older\nrestricted_uses:\n- summary: No offering coaching from multiple accounts\n  text: (c) will not offer coaching services from more than one CoachUp account without our express permission\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you (a) are 18 years of\
  \ age or older\n"
source_yaml_url: https://artifacts.apis.io/coachup/eligibility/coachup-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Coachup's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Sports
- Coaching
- Marketplace
- Fitness
- Training
- Athletics
- Two-Sided Marketplace
---
