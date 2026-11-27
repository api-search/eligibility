---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Online Services are controlled and operated from facilities in the United States. Unless otherwise explicitly stated, all materials found on Online Services are solely directed to individuals, companies, or other entities located in the United States.
  entity_types:
  - text: The Online Services are intended for individuals who are at least 18 years of age.
    type: individual
  minimum_age:
    text: The Online Services are intended for individuals who are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Personal noncommercial use only
    text: for your personal, noncommercial use only as permitted by the features of the Online Services
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
name: Valon
provenance_date: '2026-11-10'
provider_name: Valon
provider_slug: valon
slug: valon-eligibility
source_date: '2026-11-10'
source_filename: valon-eligibility.yml
source_heading: Eligibility
source_page: https://lending.servicedbycarrington.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Valon\naid: valon\nurl: https://lending.servicedbycarrington.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Online Services are controlled and operated from facilities in the United States. Unless otherwise explicitly\n    stated, all materials found on Online Services are solely directed to individuals, companies, or other entities\n    located in the United States.\nentity_types:\n- type: individual\n  text: The Online Services are intended for individuals who are at least 18 years of age.\nrestricted_uses:\n- summary: Personal noncommercial\
  \ use only\n  text: for your personal, noncommercial use only as permitted by the features of the Online Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Online Services are intended for individuals who are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/valon/eligibility/valon-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Valon's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Mortgage
- Loan Servicing
- Lending
- Fintech
- Real Estate
- Insurance
- Agentic Tools
- MCP
- Open Source
---
