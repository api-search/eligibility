---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: 'By using the Services, you represent and warrant that: (i) you are 18 years of age or older or are at least of the legally required age in the jurisdiction in which you reside'
    value: '18'
  restricted_uses:
  - summary: Prohibited activities
    text: violating any international, federal, provincial or state regulations, rules, laws, or local ordinances
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
name: TourHero
provenance_date: '2026-11-10'
provider_name: TourHero
provider_slug: tourhero
slug: tourhero-eligibility
source_date: '2026-11-10'
source_filename: tourhero-eligibility.yml
source_heading: Eligibility
source_page: https://www.tourhero.com/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TourHero\naid: tourhero\nurl: https://www.tourhero.com/en/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited activities\n  text: violating any international, federal, provincial or state regulations, rules, laws, or local ordinances\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: 'By using the Services, you represent and warrant that: (i) you are 18 years of age or older or are at least\n    of the legally required age in the\
  \ jurisdiction in which you reside'\n"
source_yaml_url: https://artifacts.apis.io/tourhero/eligibility/tourhero-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from TourHero's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Travel
- Group Travel
- Retreats
- Booking
- Creator Economy
- Consumer
---
