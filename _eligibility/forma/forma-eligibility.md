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
  restricted_uses:
  - summary: Customer compliance with laws
    text: It is Customer’s sole responsibility and duty to ensure compliance with all applicable laws and regulations, including but not limited to ERISA, COBRA, HIPAA
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
name: Forma
provenance_date: '2026-11-09'
provider_name: Forma
provider_slug: forma
slug: forma-eligibility
source_date: '2026-11-09'
source_filename: forma-eligibility.yml
source_heading: Eligibility
source_page: https://www.joinforma.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Forma\naid: forma\nurl: https://www.joinforma.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Customer compliance with laws\n  text: It is Customer’s sole responsibility and duty to ensure compliance with all applicable laws and regulations,\n    including but not limited to ERISA, COBRA, HIPAA\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/forma/eligibility/forma-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Forma's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Human Resources
- Employee Benefits
- Lifestyle Spending Accounts
- Flexible Spending Accounts
- Health Benefits
- HRIS Integration
- SCIM
---
