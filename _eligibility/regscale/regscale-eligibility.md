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
  - summary: Personal non-commercial use only
    text: You may view, download and copy information and materials available on this website solely for your personal, non-commercial use.
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
name: RegScale
provenance_date: '2026-11-10'
provider_name: RegScale
provider_slug: regscale
slug: regscale-eligibility
source_date: '2026-11-10'
source_filename: regscale-eligibility.yml
source_heading: Eligibility
source_page: https://regscale.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RegScale\naid: regscale\nurl: https://regscale.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Personal non-commercial use only\n  text: You may view, download and copy information and materials available on this website solely for your personal,\n    non-commercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/regscale/eligibility/regscale-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from RegScale's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Compliance
- Governance Risk and Compliance
- Continuous Controls Monitoring
- Security
- FedRAMP
- OSCAL
- Risk Management
- Audit
- Compliance as Code
- Vulnerability Management
- Government
---
