---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accepting these Terms and using or accessing the Services and Content on behalf of a company, organization, government, or other legal entity, you represent and warrant that you are authorized to do so
    type: other
  minimum_age:
    text: You may access and use the Services and Content only if you are at least 18 years of age and of sound mind
    value: '18'
  restricted_uses:
  - summary: Use only in compliance with law
    text: You may use and access the Services and Content only in compliance with these Terms and all applicable local, state, national, and international laws, rules, and regulations.
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
name: Citizen
provenance_date: '2026-11-09'
provider_name: Citizen
provider_slug: citizen
slug: citizen-eligibility
source_date: '2026-11-09'
source_filename: citizen-eligibility.yml
source_heading: Eligibility
source_page: https://citizen.com/privacy/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Citizen\naid: citizen\nurl: https://citizen.com/privacy/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: If you are accepting these Terms and using or accessing the Services and Content on behalf of a company,\n    organization, government, or other legal entity, you represent and warrant that you are authorized to do so\nrestricted_uses:\n- summary: Use only in compliance with law\n  text: You may use and access the Services and Content only in compliance with these Terms and all applicable local,\n    state, national,\
  \ and international laws, rules, and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may access and use the Services and Content only if you are at least 18 years of age and of sound mind\n"
source_yaml_url: https://artifacts.apis.io/citizen/eligibility/citizen-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Citizen's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Public Safety
- Safety
- Mobile App
- Location Based Services
- Real-time Alerts
- Consumer
- Emergency
---
