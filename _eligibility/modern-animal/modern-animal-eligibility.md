---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: IMPORTANT NOTICE REGARDING ARBITRATION FOR U.S. CUSTOMERS
  entity_types:
  - text: You may use the Services only if you are 18 years or older and capable of forming a binding contract with Modern Animal
    type: individual
  minimum_age:
    text: You may use the Services only if you are 18 years or older
    value: '18'
  restricted_uses:
  - summary: Membership personal use only
    text: Membership services are intended and authorized only for personal, non-transferrable, not-for-resale use only.
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
name: Modern Animal
provenance_date: '2026-11-10'
provider_name: Modern Animal
provider_slug: modern-animal
slug: modern-animal-eligibility
source_date: '2026-11-10'
source_filename: modern-animal-eligibility.yml
source_heading: Eligibility
source_page: https://www.modernanimal.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Modern Animal\naid: modern-animal\nurl: https://www.modernanimal.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: IMPORTANT NOTICE REGARDING ARBITRATION FOR U.S. CUSTOMERS\nentity_types:\n- type: individual\n  text: You may use the Services only if you are 18 years or older and capable of forming a binding contract with\n    Modern Animal\nrestricted_uses:\n- summary: Membership personal use only\n  text: Membership services are intended and authorized only for personal, non-transferrable, not-for-resale use\n    only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may use the Services only if you are 18 years or older\n"
source_yaml_url: https://artifacts.apis.io/modern-animal/eligibility/modern-animal-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Modern Animal's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Veterinary
- Pet Care
- Healthcare
- Membership
- Telehealth
---
