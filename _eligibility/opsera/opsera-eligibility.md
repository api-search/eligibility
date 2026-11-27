---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: (i) by any individual or entity in any country to which the United States has embargoed goods; or (ii) by anyone on the U.S. Treasury Department’s list of specially designated nationals
  minimum_age:
    text: THE OPSERA ASSETS ARE INTENDED FOR THE CUSTOMER AND ITS AUTHORIZED USERS ONLY AND ARE NOT FOR USE BY CHILDREN UNDER 13 YEARS OF AGE.
    value: '13'
  restricted_uses:
  - summary: Export-controlled and sanctioned access
    text: Customer may not access or use the Opsera Assets or any underlying information or technology except in full compliance with all applicable United States export control laws.
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
name: Opsera
provenance_date: '2026-11-10'
provider_name: Opsera
provider_slug: opsera
slug: opsera-eligibility
source_date: '2026-11-10'
source_filename: opsera-eligibility.yml
source_heading: Eligibility
source_page: https://opsera.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Opsera\naid: opsera\nurl: https://opsera.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: (i) by any individual or entity in any country to which the United States has embargoed goods; or (ii) by\n    anyone on the U.S. Treasury Department’s list of specially designated nationals\nentity_types: []\nrestricted_uses:\n- summary: Export-controlled and sanctioned access\n  text: Customer may not access or use the Opsera Assets or any underlying information or technology except in full\n    compliance with all applicable United States export control laws.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: THE OPSERA ASSETS ARE INTENDED FOR THE CUSTOMER AND ITS AUTHORIZED USERS ONLY AND ARE NOT FOR USE BY CHILDREN\n    UNDER 13 YEARS OF AGE.\n"
source_yaml_url: https://artifacts.apis.io/opsera/eligibility/opsera-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Opsera's own page on 2026-11-10.
synthetic: false
tags:
- Company
- DevOps
- CI/CD
- DevSecOps
- Pipeline Orchestration
- Developer Tools
- Software Delivery
- Governance
- MCP
- AI Agents
---
