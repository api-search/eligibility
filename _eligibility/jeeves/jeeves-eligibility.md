---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    - BR
    - CA
    - MX
    - CO
    - US
    text: the EEA, the United Kingdom, Brazil, Canada, Mexico, Colombia, and the United States
  entity_types:
  - text: Our products and services are intended for use by businesses and their authorized representatives.
    type: business
  minimum_age:
    text: If you are under the age of 16 (or the applicable age of digital consent in your jurisdiction, if higher), you may not open an account or use our products or services
    value: '16'
  verification:
    approval_required: null
    kyb: true
    kyc: true
    text: To open a Jeeves account and to comply with our know-your-customer (KYC) and know-your-business (KYB) obligations
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Jeeves
provenance_date: '2026-11-09'
provider_name: Jeeves
provider_slug: jeeves
slug: jeeves-eligibility
source_date: '2026-11-09'
source_filename: jeeves-eligibility.yml
source_heading: Eligibility
source_page: https://legal.tryjeeves.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Jeeves\naid: jeeves\nurl: https://legal.tryjeeves.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - GB\n  - BR\n  - CA\n  - MX\n  - CO\n  - US\n  excluded: []\n  text: the EEA, the United Kingdom, Brazil, Canada, Mexico, Colombia, and the United States\nentity_types:\n- type: business\n  text: Our products and services are intended for use by businesses and their authorized representatives.\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: true\n  approval_required: null\n  text: To open a Jeeves account and to comply with our know-your-customer (KYC) and know-your-business\
  \ (KYB) obligations\nminimum_age:\n  value: '16'\n  text: If you are under the age of 16 (or the applicable age of digital consent in your jurisdiction, if higher),\n    you may not open an account or use our products or services\n"
source_yaml_url: https://artifacts.apis.io/jeeves/eligibility/jeeves-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Jeeves's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Corporate Cards
- Expense Management
- Cross-Border Payments
- Spend Management
- Global Payments
- Stablecoins
- Financial Services
- Corporate Credit
---
