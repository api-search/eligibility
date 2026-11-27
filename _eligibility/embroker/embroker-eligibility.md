---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Embroker has subsidiaries which are licensed as applicable in various U.S. states. This website is not intended as a solicitation for insurance or claims services in any state or province where Embroker is not licensed.
  entity_types:
  - text: You warrant that you are at least 18 years of age and can enter into binding contracts for insurance or other goods.
    type: individual
  minimum_age:
    text: You warrant that you are at least 18 years of age and can enter into binding contracts for insurance or other goods.
    value: '18'
  restricted_uses:
  - summary: Illegal or fraudulent purposes
    text: not to use the Services for false, fraudulent or illegal purposes
  - summary: Sanctioned parties
    text: Embroker does not provide insurance brokerage or other services to governments, governmental agencies, businesses, individuals, other groups, or any of their agents that are subject to U.S. trade sanctions.
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
name: Embroker
provenance_date: '2026-11-09'
provider_name: Embroker
provider_slug: embroker
slug: embroker-eligibility
source_date: '2026-11-09'
source_filename: embroker-eligibility.yml
source_heading: Eligibility
source_page: https://www.embroker.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Embroker\naid: embroker\nurl: https://www.embroker.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Embroker has subsidiaries which are licensed as applicable in various U.S. states. This website is not intended\n    as a solicitation for insurance or claims services in any state or province where Embroker is not licensed.\nentity_types:\n- type: individual\n  text: You warrant that you are at least 18 years of age and can enter into binding contracts for insurance or\n    other goods.\nrestricted_uses:\n- summary: Illegal or fraudulent purposes\n  text: not to use the\
  \ Services for false, fraudulent or illegal purposes\n- summary: Sanctioned parties\n  text: Embroker does not provide insurance brokerage or other services to governments, governmental agencies, businesses,\n    individuals, other groups, or any of their agents that are subject to U.S. trade sanctions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You warrant that you are at least 18 years of age and can enter into binding contracts for insurance or\n    other goods.\n"
source_yaml_url: https://artifacts.apis.io/embroker/eligibility/embroker-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Embroker's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Business Insurance
- Commercial Insurance
- Insurtech
- Digital Insurance
- Brokerage
- Managing General Agent
- Cyber Insurance
- Professional Liability
- Directors and Officers
- Startups
- Law Firms
- Risk Management
---
