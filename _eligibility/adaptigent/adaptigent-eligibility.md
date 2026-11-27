---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: This Website may describe products that are not available worldwide.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial use requires consent
    text: You will not use this Website for any other purpose, including any commercial purpose, without Adaptigent’s prior written consent.
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
name: Adaptigent
provenance_date: '2026-11-09'
provider_name: Adaptigent
provider_slug: adaptigent
slug: adaptigent-eligibility
source_date: '2026-11-09'
source_filename: adaptigent-eligibility.yml
source_heading: Eligibility
source_page: https://www.adaptigent.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Adaptigent\naid: adaptigent\nurl: https://www.adaptigent.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: This Website may describe products that are not available worldwide.\nentity_types: []\nrestricted_uses:\n- summary: Commercial use requires consent\n  text: You will not use this Website for any other purpose, including any commercial purpose, without Adaptigent’s\n    prior written consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/adaptigent/eligibility/adaptigent-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Adaptigent's own page on 2026-11-09.
synthetic: false
tags:
- Mainframe
- Integration
- API Gateway
- Legacy Systems
- Enterprise
- No-Code
- Middleware
---
