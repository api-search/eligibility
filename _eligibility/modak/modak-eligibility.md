---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To create a Modak Account as a Parent Accountholder, you must be at least 18 years old (or the age of majority in your state of residence)
    type: individual
  minimum_age:
    text: you must be at least 18 years old (or the age of majority in your state of residence)
    value: '18'
  restricted_uses:
  - summary: Illegal, fraudulent or gambling use
    text: gambling (if underage or in prohibited jurisdictions), or funding terrorist activities
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: Banking products and services made available through the Service are subject to approval by the applicable Sponsor Bank and may require additional activation steps.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Modak
provenance_date: '2026-11-10'
provider_name: Modak
provider_slug: modak
slug: modak-eligibility
source_date: '2026-11-10'
source_filename: modak-eligibility.yml
source_heading: Eligibility
source_page: https://www.modakmakers.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Modak\naid: modak\nurl: https://www.modakmakers.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To create a Modak Account as a Parent Accountholder, you must be at least 18 years old (or the age of majority\n    in your state of residence)\nrestricted_uses:\n- summary: Illegal, fraudulent or gambling use\n  text: gambling (if underage or in prohibited jurisdictions), or funding terrorist activities\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: Banking products and services\
  \ made available through the Service are subject to approval by the applicable\n    Sponsor Bank and may require additional activation steps.\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years old (or the age of majority in your state of residence)\n"
source_yaml_url: https://artifacts.apis.io/modak/eligibility/modak-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Modak's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Consumer
- Banking
- Debit Cards
- Kids
- Allowance
- Personal Finance
- Mobile App
---
