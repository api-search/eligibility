---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Fraudulent activity
    text: we suspect that you have engaged in fraudulent activity in connection with the Brinqa websites or any Brinqa service.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 'If required by Brinqa, each user must: (a) provide true, accurate, current and complete information on the Service’s registration form'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Brinqa
provenance_date: '2026-11-09'
provider_name: Brinqa
provider_slug: brinqa
slug: brinqa-eligibility
source_date: '2026-11-09'
source_filename: brinqa-eligibility.yml
source_heading: Eligibility
source_page: https://www.brinqa.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brinqa\naid: brinqa\nurl: https://www.brinqa.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Fraudulent activity\n  text: we suspect that you have engaged in fraudulent activity in connection with the Brinqa websites or any Brinqa\n    service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 'If required by Brinqa, each user must: (a) provide true, accurate, current and complete information on\n    the Service’s registration form'\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/brinqa/eligibility/brinqa-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Brinqa's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- Vulnerability Management
- Exposure Management
- Cyber Risk
- Risk Management
- Security
- GraphQL
---
