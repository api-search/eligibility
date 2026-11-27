---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This Agreement applies to individuals who are searching for employment or using the site for their own personal benefit.
    type: individual
  - text: If you are a client of HireArt and using HireArt’s services in order to hire individuals, your use of the Site and the Services will be governed by a separate written agreement entered into between you and HireArt.
    type: business
  minimum_age:
    text: you are eighteen (18) years of age or older.
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: you may access and use the Services only for lawful purposes.
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
name: HireArt
provenance_date: '2026-11-09'
provider_name: HireArt
provider_slug: hireart
slug: hireart-eligibility
source_date: '2026-11-09'
source_filename: hireart-eligibility.yml
source_heading: Eligibility
source_page: https://www.hireart.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HireArt\naid: hireart\nurl: https://www.hireart.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: This Agreement applies to individuals who are searching for employment or using the site for their own personal\n    benefit.\n- type: business\n  text: If you are a client of HireArt and using HireArt’s services in order to hire individuals, your use of the\n    Site and the Services will be governed by a separate written agreement entered into between you and HireArt.\nrestricted_uses:\n- summary: Lawful purposes only\n  text:\
  \ you may access and use the Services only for lawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are eighteen (18) years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/hireart/eligibility/hireart-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from HireArt's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Workforce Management
- Staffing
- Employer of Record
- Vendor Management System
- Contingent Workforce
- Recruiting
- Compliance
---
