---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - GB
    text: All gift cards sold through our catalog are valid in the United States (if labeled in dollars) or the United Kingdom (if labeled in GBP).
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Users not legally able to contract
    text: (f) use JIFITI PRODUCTS if you are not legally permitted to form legally binding contracts, or are temporarily or indefinitely suspended from using JIFITI PRODUCTS;
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
name: Jifiti
provenance_date: '2026-11-09'
provider_name: Jifiti
provider_slug: jifiti
slug: jifiti-eligibility
source_date: '2026-11-09'
source_filename: jifiti-eligibility.yml
source_heading: Eligibility
source_page: https://www.jifiti.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Jifiti\naid: jifiti\nurl: https://www.jifiti.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - GB\n  excluded: []\n  text: All gift cards sold through our catalog are valid in the United States (if labeled in dollars) or the United\n    Kingdom (if labeled in GBP).\nentity_types: []\nrestricted_uses:\n- summary: Users not legally able to contract\n  text: (f) use JIFITI PRODUCTS if you are not legally permitted to form legally binding contracts, or are temporarily\n    or indefinitely suspended from using JIFITI PRODUCTS;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/jifiti/eligibility/jifiti-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Jifiti's own page on 2026-11-09.
synthetic: false
tags:
- Banking
- Buy Now Pay Later
- Embedded Finance
- Embedded Lending
- Fintech
- Lending
- Payments
- POS Financing
- White Label
---
