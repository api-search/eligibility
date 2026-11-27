---
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - RU
    - CN
    served:
    - CA
    text: 'Customer may access and use the Alexi Solution only in Canada. Customer will not permit any Permitted User to access and use the Alexi SaaS Services or other Alexi Property from Russia, China, or any country: (A) subject to any embargo or sanction by the United States or Canada'
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High Risk Activities
    text: (B) for any High Risk Activities
  - summary: Sanctioned countries and restricted parties
    text: Customer will not permit any Permitted User to access and use the Alexi SaaS Services or other Alexi Property from Russia, China, or any country
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- RU
- CN
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Alexi
provenance_date: '2026-11-09'
provider_name: Alexi
provider_slug: alexi
slug: alexi-eligibility
source_date: '2026-11-09'
source_filename: alexi-eligibility.yml
source_heading: Eligibility
source_page: https://www.alexi.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Alexi\naid: alexi\nurl: https://www.alexi.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - CA\n  excluded:\n  - RU\n  - CN\n  text: 'Customer may access and use the Alexi Solution only in Canada. Customer will not permit any Permitted User\n    to access and use the Alexi SaaS Services or other Alexi Property from Russia, China, or any country: (A) subject\n    to any embargo or sanction by the United States or Canada'\nentity_types: []\nrestricted_uses:\n- summary: High Risk Activities\n  text: (B) for any High Risk Activities\n- summary: Sanctioned countries and\
  \ restricted parties\n  text: Customer will not permit any Permitted User to access and use the Alexi SaaS Services or other Alexi Property\n    from Russia, China, or any country\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/alexi/eligibility/alexi-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from Alexi's own page on 2026-11-09.
synthetic: false
tags:
- Legal
- Legal Tech
- Legal AI
- Litigation
- Legal Research
- Brief Drafting
- Law Firms
- Document Drafting
- RAG
- AI Agents
- Private AI
- Single Tenant
- Knowledge Management
- Canada
- Toronto
---
