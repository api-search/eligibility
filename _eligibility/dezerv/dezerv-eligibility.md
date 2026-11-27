---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: only residents of India, who are individual / natural persons who can enter into legally binding contract under Section 11 of the Indian Contract Act, 1872 shall be eligible to use Our Services
  entity_types:
  - text: only residents of India, who are individual / natural persons who can enter into legally binding contract under Section 11 of the Indian Contract Act, 1872 shall be eligible to use Our Services and transact on the Platform.
    type: individual
  minimum_age:
    text: null
    value: null
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
name: Dezerv
provenance_date: '2026-11-09'
provider_name: Dezerv
provider_slug: dezerv
slug: dezerv-eligibility
source_date: '2026-11-09'
source_filename: dezerv-eligibility.yml
source_heading: Eligibility
source_page: https://www.dezerv.in/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dezerv\naid: dezerv\nurl: https://www.dezerv.in/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: only residents of India, who are individual / natural persons who can enter into legally binding contract\n    under Section 11 of the Indian Contract Act, 1872 shall be eligible to use Our Services\nentity_types:\n- type: individual\n  text: only residents of India, who are individual / natural persons who can enter into legally binding contract\n    under Section 11 of the Indian Contract Act, 1872 shall be eligible to use Our Services and transact on the\n    Platform.\n\
  restricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dezerv/eligibility/dezerv-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from Dezerv's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Services
- Wealth Management
- Investment
- Portfolio Management
- Mutual Funds
- Fintech
- India
- Financial Services
---
