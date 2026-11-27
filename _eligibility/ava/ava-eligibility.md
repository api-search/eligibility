---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Your approval for the Ava Credit Builder Card or Save and Build Account is not guaranteed. Successfully linking your bank account to Ava via Plaid is a condition to any such approval.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ava
provenance_date: '2026-11-09'
provider_name: Ava
provider_slug: ava
slug: ava-eligibility
source_date: '2026-11-09'
source_filename: ava-eligibility.yml
source_heading: Eligibility
source_page: https://www.meetava.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ava\naid: ava\nurl: https://www.meetava.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Your approval for the Ava Credit Builder Card or Save and Build Account is not guaranteed. Successfully\n    linking your bank account to Ava via Plaid is a condition to any such approval.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ava/eligibility/ava-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from Ava's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Credit Building
- Consumer Finance
- Credit Score
- Personal Finance
- Lending
- Mobile App
---
