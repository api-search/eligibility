---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You must be a US citizen or a legal US resident
  entity_types:
  - text: You must be at least eighteen (18) years old or the age of majority in your jurisdiction
    type: individual
  minimum_age:
    text: You must be at least eighteen (18) years old or the age of majority in your jurisdiction
    value: '18'
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: Credit Builder and Line of Credit accounts are subject to approval by Coastal Community Bank.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Brigit
provenance_date: '2026-11-09'
provider_name: Brigit
provider_slug: brigit
slug: brigit-eligibility
source_date: '2026-11-09'
source_filename: brigit-eligibility.yml
source_heading: Eligibility
source_page: https://www.hellobrigit.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brigit\naid: brigit\nurl: https://www.hellobrigit.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You must be a US citizen or a legal US resident\nentity_types:\n- type: individual\n  text: You must be at least eighteen (18) years old or the age of majority in your jurisdiction\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: Credit Builder and Line of Credit accounts are subject to approval by Coastal Community Bank.\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years old\
  \ or the age of majority in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/brigit/eligibility/brigit-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Brigit's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Consumer Finance
- Cash Advance
- Credit Building
- Personal Finance
- Budgeting
- Mobile App
---
