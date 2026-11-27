---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: In respect of recipients resident in the UK, this communication is aimed solely at high-net worth companies, associations and trusts
  entity_types:
  - text: If you are accessing and using the Services on behalf of a company (such as your employer) or other legal entity, you represent and warrant that you have the authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: You may use the Services only if you are 18 years or older and capable of forming a binding contract with Talos
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
name: Talos
provenance_date: '2026-11-10'
provider_name: Talos
provider_slug: talos
slug: talos-eligibility
source_date: '2026-11-10'
source_filename: talos-eligibility.yml
source_heading: Eligibility
source_page: https://www.talos.com/legals/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Talos\naid: talos\nurl: https://www.talos.com/legals/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: In respect of recipients resident in the UK, this communication is aimed solely at high-net worth companies,\n    associations and trusts\nentity_types:\n- type: business\n  text: If you are accessing and using the Services on behalf of a company (such as your employer) or other legal\n    entity, you represent and warrant that you have the authority to bind that entity to these Terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: You may use the Services only if you are 18 years or older and capable of forming a binding contract with\n    Talos\n"
source_yaml_url: https://artifacts.apis.io/talos/eligibility/talos-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Talos's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Digital Assets
- Cryptocurrency
- Trading
- OEMS
- Institutional Finance
- Market Data
- FIX
- WebSocket
- Fintech
- Crypto Infrastructure
- Portfolio Management
---
