---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: When you create an account with us, you guarantee that you are above the age of 18
    value: '18'
  restricted_uses:
  - summary: Fraudulent or illegal transactions
    text: We reserve the right to refuse or cancel your order if fraud or an unauthorized or illegal transaction is suspected.
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
name: Ahsuite
provenance_date: '2026-11-09'
provider_name: Ahsuite
provider_slug: ahsuite-com
slug: ahsuite-com-eligibility
source_date: '2026-11-09'
source_filename: ahsuite-com-eligibility.yml
source_heading: Eligibility
source_page: https://ahsuite.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ahsuite\naid: ahsuite-com\nurl: https://ahsuite.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Fraudulent or illegal transactions\n  text: We reserve the right to refuse or cancel your order if fraud or an unauthorized or illegal transaction is\n    suspected.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: When you create an account with us, you guarantee that you are above the age of 18\n"
source_yaml_url: https://artifacts.apis.io/ahsuite-com/eligibility/ahsuite-com-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Ahsuite's own page on 2026-11-09.
synthetic: false
tags:
- Client Portal
- Software-as-a-Service
- Collaboration
- AI Integration
- Accounting
---
