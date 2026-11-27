---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You must be an individual of at least 18 years of age and reside in the United States, on a United States military base, or in a United States territory in order to use the Service or the App.
  entity_types:
  - text: You must be an individual of at least 18 years of age and reside in the United States
    type: individual
  minimum_age:
    text: You must be an individual of at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Personal use only
    text: for your personal use and not for any commercial or business purpose
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: We will verify your identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Brightmoney
provenance_date: '2026-11-09'
provider_name: Brightmoney
provider_slug: brightmoney
slug: brightmoney-eligibility
source_date: '2026-11-09'
source_filename: brightmoney-eligibility.yml
source_heading: Eligibility
source_page: https://www.brightmoney.co/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brightmoney\naid: brightmoney\nurl: https://www.brightmoney.co/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You must be an individual of at least 18 years of age and reside in the United States, on a United States\n    military base, or in a United States territory in order to use the Service or the App.\nentity_types:\n- type: individual\n  text: You must be an individual of at least 18 years of age and reside in the United States\nrestricted_uses:\n- summary: Personal use only\n  text: for your personal use and not for any commercial\
  \ or business purpose\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: We will verify your identity.\nminimum_age:\n  value: '18'\n  text: You must be an individual of at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/brightmoney/eligibility/brightmoney-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Brightmoney's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Consumer Finance
- Credit Building
- Debt Management
- Lending
- Personal Finance
- Artificial Intelligence
---
