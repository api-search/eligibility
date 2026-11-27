---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Access to the Site is reserved for eligible counterparties or professional clients within the meaning of the regulations of the French Financial Markets Authority
    type: business
  - text: Access to the Site is reserved for adult U.S. institutional investors (Major U.S. Institutional Investors – MII)
    type: business
  minimum_age:
    text: Access to the Site is reserved for adults.
    value: adult
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
name: Quantilia
provenance_date: '2026-11-10'
provider_name: Quantilia
provider_slug: quantilia
slug: quantilia-eligibility
source_date: '2026-11-10'
source_filename: quantilia-eligibility.yml
source_heading: Eligibility
source_page: https://www.quantilia.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Quantilia\naid: quantilia\nurl: https://www.quantilia.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Access to the Site is reserved for eligible counterparties or professional clients within the meaning of\n    the regulations of the French Financial Markets Authority\n- type: business\n  text: Access to the Site is reserved for adult U.S. institutional investors (Major U.S. Institutional Investors\n    – MII)\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: adult\n  text: Access to the Site is reserved for adults.\n"
source_yaml_url: https://artifacts.apis.io/quantilia/eligibility/quantilia-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Quantilia's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Ai Data
- Financial Data
- Portfolio Reporting
- Investment Management
- Asset Management
- Risk Analytics
- ESG
- Private Markets
- Regulatory Reporting
- Data Aggregation
- France
---
