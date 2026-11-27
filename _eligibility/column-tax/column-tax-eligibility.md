---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service is designed to be used by users who are legal residents of the United States only; however, it may be accessed from countries around the world
  entity_types:
  - text: you are of legal age to form a binding contract with Column Tax
    type: individual
  minimum_age:
    text: you are of legal age to form a binding contract with Column Tax
    value: null
  restricted_uses:
  - summary: No false identity or unauthorized filing
    text: You agree not to use a false identity, or provide Tax Filing Information on behalf of someone other than yourself, unless allowed under applicable law (e.g., joint tax filing).
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
name: Column Tax
provenance_date: '2026-11-09'
provider_name: Column Tax
provider_slug: column-tax
slug: column-tax-eligibility
source_date: '2026-11-09'
source_filename: column-tax-eligibility.yml
source_heading: Eligibility
source_page: https://www.columntax.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Column Tax\naid: column-tax\nurl: https://www.columntax.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Service is designed to be used by users who are legal residents of the United States only; however,\n    it may be accessed from countries around the world\nentity_types:\n- type: individual\n  text: you are of legal age to form a binding contract with Column Tax\nrestricted_uses:\n- summary: No false identity or unauthorized filing\n  text: You agree not to use a false identity, or provide Tax Filing Information on behalf of someone other\
  \ than\n    yourself, unless allowed under applicable law (e.g., joint tax filing).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are of legal age to form a binding contract with Column Tax\n"
source_yaml_url: https://artifacts.apis.io/column-tax/eligibility/column-tax-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Column Tax's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Tax
- Tax Filing
- Embedded Finance
- E-File
- Financial Services
- Banking
- API-First
---
