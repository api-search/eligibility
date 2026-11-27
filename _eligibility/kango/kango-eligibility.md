---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not, you've received your parent's or guardian's permission to use the Services
    type: individual
  minimum_age:
    text: use of the Services is restricted to adults over the age of 18.
    value: '18'
  restricted_uses:
  - summary: Impersonation and transfer restrictions
    text: You may not select as your Kango User ID a name that you don't have the right to use, or another person's name with the intent to impersonate that person. You may not transfer your account to anyone else without our prior written permission.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Kango conducts background screenings of those Users who register as Drivers, including criminal background checks, motor vehicle background checks, identity verification
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Kango
provenance_date: '2026-11-09'
provider_name: Kango
provider_slug: kango
slug: kango-eligibility
source_date: '2026-11-09'
source_filename: kango-eligibility.yml
source_heading: Eligibility
source_page: https://www.kangoapp.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kango\naid: kango\nurl: https://www.kangoapp.com/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not,\n    you've received your parent's or guardian's permission to use the Services\nrestricted_uses:\n- summary: Impersonation and transfer restrictions\n  text: You may not select as your Kango User ID a name that you don't have the right to use, or another person's\n    name with the intent to impersonate that person. You may\
  \ not transfer your account to anyone else without our\n    prior written permission.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Kango conducts background screenings of those Users who register as Drivers, including criminal background\n    checks, motor vehicle background checks, identity verification\nminimum_age:\n  value: '18'\n  text: use of the Services is restricted to adults over the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/kango/eligibility/kango-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Kango's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Childcare
- Transportation
- Ride Hailing
- Family
- Mobility
- On-Demand
---
