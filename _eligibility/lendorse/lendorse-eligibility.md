---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you sign the contract electronically and send it to us together with your documents (passport, admission letter, etc.)
    type: individual
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Once we have all the information, we make a decision.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Lendorse
provenance_date: '2026-11-09'
provider_name: Lendorse
provider_slug: lendorse
slug: lendorse-eligibility
source_date: '2026-11-09'
source_filename: lendorse-eligibility.yml
source_heading: Eligibility
source_page: https://lendorse.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lendorse\naid: lendorse\nurl: https://lendorse.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you sign the contract electronically and send it to us together with your documents (passport, admission\n    letter, etc.)\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Once we have all the information, we make a decision.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/lendorse/eligibility/lendorse-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from Lendorse's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Lending
- Education
- Student Finance
- Income Share Agreements
- Financial Inclusion
- Germany
- Europe
---
