---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Company has no control over jurisdictional blocks which may prevent User from utilizing the Website.
  entity_types:
  - text: By agreeing to these terms, user hereby certifies that user is at least 18 years of age.
    type: individual
  minimum_age:
    text: BY AGREEING TO THESE TERMS, USER HEREBY CERTIFIES THAT USER IS AT LEAST 18 YEARS OF AGE.
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: User agrees to use the Platform only for lawful purposes, comply with all rules governing any transactions on and through the Platform and comply with the law.
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
name: 3Jane
provenance_date: '2026-11-09'
provider_name: 3Jane
provider_slug: 3jane
slug: 3jane-eligibility
source_date: '2026-11-09'
source_filename: 3jane-eligibility.yml
source_heading: Eligibility
source_page: https://www.3jane.xyz/pdf/terms-of-service.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 3Jane\naid: 3jane\nurl: https://www.3jane.xyz/pdf/terms-of-service.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Company has no control over jurisdictional blocks which may prevent User from utilizing the Website.\nentity_types:\n- type: individual\n  text: By agreeing to these terms, user hereby certifies that user is at least 18 years of age.\nrestricted_uses:\n- summary: Lawful purposes only\n  text: User agrees to use the Platform only for lawful purposes, comply with all rules governing any transactions\n    on and through the Platform and comply with the law.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: BY AGREEING TO THESE TERMS, USER HEREBY CERTIFIES THAT USER IS AT LEAST 18 YEARS OF AGE.\n"
source_yaml_url: https://artifacts.apis.io/3jane/eligibility/3jane-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from 3Jane's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Crypto Defi
- DeFi
- Lending
- Credit
- Uncollateralized Lending
- Stablecoins
- Money Market
- Ethereum
- Yield
---
