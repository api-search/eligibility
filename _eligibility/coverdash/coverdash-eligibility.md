---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Coverdash is licensed as an insurance broker or agent in various U.S. states. This website is not intended as a solicitation for insurance in any state or province where Coverdash is not licensed.
  entity_types:
  - text: You warrant that you are at least 18 years of age and can enter into binding contracts for insurance or other goods.
    type: individual
  - text: Coverdash does not provide insurance services, solutions or products to any business entity that is based outside of the U.S.
    type: business
  minimum_age:
    text: You warrant that you are at least 18 years of age and can enter into binding contracts for insurance or other goods.
    value: '18'
  restricted_uses:
  - summary: Trade sanctions
    text: Coverdash does not provide insurance brokerage or other services to governments, governmental agencies, businesses, individuals, other groups, or any of their agents that are subject to U.S. trade sanctions.
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
name: Coverdash
provenance_date: '2026-11-09'
provider_name: Coverdash
provider_slug: coverdash
slug: coverdash-eligibility
source_date: '2026-11-09'
source_filename: coverdash-eligibility.yml
source_heading: Eligibility
source_page: https://www.coverdash.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coverdash\naid: coverdash\nurl: https://www.coverdash.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Coverdash is licensed as an insurance broker or agent in various U.S. states. This website is not intended\n    as a solicitation for insurance in any state or province where Coverdash is not licensed.\nentity_types:\n- type: individual\n  text: You warrant that you are at least 18 years of age and can enter into binding contracts for insurance or\n    other goods.\n- type: business\n  text: Coverdash does not provide insurance services, solutions or products to any business\
  \ entity that is based\n    outside of the U.S.\nrestricted_uses:\n- summary: Trade sanctions\n  text: Coverdash does not provide insurance brokerage or other services to governments, governmental agencies,\n    businesses, individuals, other groups, or any of their agents that are subject to U.S. trade sanctions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You warrant that you are at least 18 years of age and can enter into binding contracts for insurance or\n    other goods.\n"
source_yaml_url: https://artifacts.apis.io/coverdash/eligibility/coverdash-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Coverdash's own page on 2026-11-09.
synthetic: false
tags:
- Insurtech
- Business Insurance
- Software-as-a-Service
- API Platform
- Small Business
---
