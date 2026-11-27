---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: YOU HAVE THE AUTHORITY TO OR ARE AUTHORIZED TO BIND THE CUSTOMER TO THE EULA
    type: business
  minimum_age:
    text: ARE 18 YEARS OF AGE OR OLDER
    value: '18'
  restricted_uses:
  - summary: No illegal use
    text: You agree that you will not use the Service for any illegal purpose.
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
name: Capstack
provenance_date: '2026-11-09'
provider_name: Capstack
provider_slug: capstack
slug: capstack-eligibility
source_date: '2026-11-09'
source_filename: capstack-eligibility.yml
source_heading: Eligibility
source_page: https://capstack.ai/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Capstack\naid: capstack\nurl: https://capstack.ai/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: YOU HAVE THE AUTHORITY TO OR ARE AUTHORIZED TO BIND THE CUSTOMER TO THE EULA\nrestricted_uses:\n- summary: No illegal use\n  text: You agree that you will not use the Service for any illegal purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: ARE 18 YEARS OF AGE OR OLDER\n"
source_yaml_url: https://artifacts.apis.io/capstack/eligibility/capstack-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Capstack's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Banking
- Loan Marketplace
- Loan Trading
- Loan Servicing
- Portfolio Analytics
- Credit Union
- Capital Markets
---
