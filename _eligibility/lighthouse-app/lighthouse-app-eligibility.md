---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You may use the Services only if you are residents of the United States
  entity_types:
  - text: You may use the Services only if you are residents of the United States and are 18 years or older
    type: individual
  - text: If you are accessing and using the Services on behalf of a company (such as your employer) or other legal entity, you represent and warrant that you have the authority to bind that company or other legal entity to this Agreement.
    type: business
  minimum_age:
    text: 18 years or older capable of forming a binding contract with Lighthouse
    value: '18'
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
name: Lighthouse
provenance_date: '2026-11-09'
provider_name: Lighthouse
provider_slug: lighthouse-app
slug: lighthouse-app-eligibility
source_date: '2026-11-09'
source_filename: lighthouse-app-eligibility.yml
source_heading: Eligibility
source_page: https://lighthouse.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lighthouse\naid: lighthouse-app\nurl: https://lighthouse.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You may use the Services only if you are residents of the United States\nentity_types:\n- type: individual\n  text: You may use the Services only if you are residents of the United States and are 18 years or older\n- type: business\n  text: If you are accessing and using the Services on behalf of a company (such as your employer) or other legal\n    entity, you represent and warrant that you have the authority to bind that company or other legal entity to\n    this\
  \ Agreement.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: 18 years or older capable of forming a binding contract with Lighthouse\n"
source_yaml_url: https://artifacts.apis.io/lighthouse-app/eligibility/lighthouse-app-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 4 quoted statements, read from Lighthouse's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- Fintech
- Rentals
- Cashback
---
