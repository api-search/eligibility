---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are at least 18 years of age, or, if you are under 18 years of age, that you are using the Services under the supervision of an adult who is at least 18 years of age.
    type: individual
  minimum_age:
    text: You represent and warrant that you are at least 18 years of age, or, if you are under 18 years of age, that you are using the Services under the supervision of an adult who is at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Non-commercial use only
    text: Any other use of the Services requires the prior written consent of Company.
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
name: Meitre
provenance_date: '2026-11-10'
provider_name: Meitre
provider_slug: meitre
slug: meitre-eligibility
source_date: '2026-11-10'
source_filename: meitre-eligibility.yml
source_heading: Eligibility
source_page: https://legal.meitre.com/terms-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Meitre\naid: meitre\nurl: https://legal.meitre.com/terms-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are at least 18 years of age, or, if you are under 18 years of age, that\n    you are using the Services under the supervision of an adult who is at least 18 years of age.\nrestricted_uses:\n- summary: Non-commercial use only\n  text: Any other use of the Services requires the prior written consent of Company.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are at least 18 years of age, or, if you are under 18 years of age, that\n    you are using the Services under the supervision of an adult who is at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/meitre/eligibility/meitre-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Meitre's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Restaurant
- Reservations
- Hospitality
- Booking
- Guest Management
- Revenue Management
- Food and Beverage
- Latin America
---
