---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: To use the Services, you must be a legal resident in the United States of America and physically located in a jurisdiction where participation in the Services is legal and not prohibited or restricted by law
  entity_types:
  - text: You are opening a non-transferable account solely for your personal use
    type: individual
  minimum_age:
    text: you are at least eighteen (18) years of age, or the minimum age of majority where you are located at the time of accessing the Services, whichever is greater
    value: '18'
  restricted_uses:
  - summary: Athletes and officials barred from related sport
    text: Professional or amateur athletes, sports agents, coaches, trainers, sports league referees or officials, sports team owners, sports team employees, and the immediate family members of these individuals, are prohibited from using any Services concerning the sport(s) in which they are associated.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Complete our identity-verification process.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Betr
provenance_date: '2026-11-09'
provider_name: Betr
provider_slug: betr
slug: betr-eligibility
source_date: '2026-11-09'
source_filename: betr-eligibility.yml
source_heading: Eligibility
source_page: https://www.betr.app/terms-and-conditions/picks
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Betr\naid: betr\nurl: https://www.betr.app/terms-and-conditions/picks\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: To use the Services, you must be a legal resident in the United States of America and physically located\n    in a jurisdiction where participation in the Services is legal and not prohibited or restricted by law\nentity_types:\n- type: individual\n  text: You are opening a non-transferable account solely for your personal use\nrestricted_uses:\n- summary: Athletes and officials barred from related sport\n  text: Professional or amateur athletes,\
  \ sports agents, coaches, trainers, sports league referees or officials,\n    sports team owners, sports team employees, and the immediate family members of these individuals, are prohibited\n    from using any Services concerning the sport(s) in which they are associated.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Complete our identity-verification process.\nminimum_age:\n  value: '18'\n  text: you are at least eighteen (18) years of age, or the minimum age of majority where you are located at the\n    time of accessing the Services, whichever is greater\n"
source_yaml_url: https://artifacts.apis.io/betr/eligibility/betr-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Betr's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Gaming
- Sports Betting
- Daily Fantasy Sports
- Sports
- Media
- Entertainment
- Mobile App
- Consumer
- Responsible Gaming
---
