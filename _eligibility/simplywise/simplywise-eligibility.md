---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The SimplyWise Services are intended for U.S. residents only.
  minimum_age:
    text: To use the Services you must (i) be at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: Competitive intelligence or competing products
    text: Use the Services for competitive intelligence, benchmarking, or to develop a competing product or service;
  - summary: Automated decisions without human review
    text: use AI-Generated Content as the basis for automated decision-making that adversely affects the legal rights or material interests of any individual without human review
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
name: Simplywise
provenance_date: '2026-11-10'
provider_name: Simplywise
provider_slug: simplywise
slug: simplywise-eligibility
source_date: '2026-11-10'
source_filename: simplywise-eligibility.yml
source_heading: Eligibility
source_page: https://www.simplywise.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Simplywise\naid: simplywise\nurl: https://www.simplywise.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The SimplyWise Services are intended for U.S. residents only.\nentity_types: []\nrestricted_uses:\n- summary: Competitive intelligence or competing products\n  text: Use the Services for competitive intelligence, benchmarking, or to develop a competing product or service;\n- summary: Automated decisions without human review\n  text: use AI-Generated Content as the basis for automated decision-making that adversely affects the legal rights\n  \
  \  or material interests of any individual without human review\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: To use the Services you must (i) be at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/simplywise/eligibility/simplywise-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Simplywise's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Small Business
- Receipts
- Expense Management
- Mileage Tracking
- Bookkeeping
- Artificial Intelligence
- Mobile App
---
