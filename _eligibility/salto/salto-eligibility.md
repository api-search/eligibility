---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least eighteen (18) years of age to use the Services.
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
name: Salto
provenance_date: '2026-11-10'
provider_name: Salto
provider_slug: salto
slug: salto-eligibility
source_date: '2026-11-10'
source_filename: salto-eligibility.yml
source_heading: Eligibility
source_page: https://www.salto.io/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Salto\naid: salto\nurl: https://www.salto.io/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years of age to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/salto/eligibility/salto-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from Salto's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cloud Saas
- Configuration Management
- DevOps
- Change Management
- CI/CD
- Salesforce
- NetSuite
- SaaS Management
- AI Agents
- Developer Tools
---
