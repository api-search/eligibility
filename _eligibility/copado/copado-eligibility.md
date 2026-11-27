---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: be at least 18 years of age or older
    value: '18'
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
name: Copado
provenance_date: '2026-11-09'
provider_name: Copado
provider_slug: copado
slug: copado-eligibility
source_date: '2026-11-09'
source_filename: copado-eligibility.yml
source_heading: Eligibility
source_page: https://www.copado.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Copado\naid: copado\nurl: https://www.copado.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: be at least 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/copado/eligibility/copado-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from Copado's own page on 2026-11-09.
synthetic: false
tags:
- Company
- DevOps
- Salesforce
- CI/CD
- Release Management
- Testing
- DevSecOps
- Low-Code
---
