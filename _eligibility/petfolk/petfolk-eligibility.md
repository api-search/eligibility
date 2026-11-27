---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old (or the age of majority in your state) to opt in to receive marketing text messages.
    type: individual
  minimum_age:
    text: Participants must be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Automated referral participation
    text: Use of automated systems, scripts, marco, to participate in the Program or general referrals or other non-bonafide accounts is strictly prohibited
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
name: Petfolk
provenance_date: '2026-11-10'
provider_name: Petfolk
provider_slug: petfolk
slug: petfolk-eligibility
source_date: '2026-11-10'
source_filename: petfolk-eligibility.yml
source_heading: Eligibility
source_page: https://petfolk.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Petfolk\naid: petfolk\nurl: https://petfolk.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old (or the age of majority in your state) to opt in to receive marketing\n    text messages.\nrestricted_uses:\n- summary: Automated referral participation\n  text: Use of automated systems, scripts, marco, to participate in the Program or general referrals or other non-bonafide\n    accounts is strictly prohibited\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '18'\n  text: Participants must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/petfolk/eligibility/petfolk-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Petfolk's own page on 2026-11-10.
synthetic: false
tags:
- Veterinary
- veterinary-care
- Animal Health
- Pet Care
- Pet Health
- Healthcare
- Telehealth
- Virtual Care
- Urgent Care
- Clinics
- Membership
- Consumer Health
- Mobile App
- North Carolina
---
