---
claim_count: 1
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: Subscriber shall not access or use the Hosted Services in or to countries or territories subject to U.S. trade sanctions (including without limitation Cuba, Iran, North Korea, Syria, and the Crimea, Donetsk and Luhansk regions of Ukraine)
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: RiskRecon
provenance_date: '2026-11-10'
provider_name: RiskRecon
provider_slug: riskrecon
slug: riskrecon-eligibility
source_date: '2026-11-10'
source_filename: riskrecon-eligibility.yml
source_heading: Eligibility
source_page: https://www.riskrecon.com/terms-of-use-2025
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RiskRecon\naid: riskrecon\nurl: https://www.riskrecon.com/terms-of-use-2025\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: Subscriber shall not access or use the Hosted Services in or to countries or territories subject to U.S.\n    trade sanctions (including without limitation Cuba, Iran, North Korea, Syria, and the Crimea, Donetsk and Luhansk\n    regions of Ukraine)\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/riskrecon/eligibility/riskrecon-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from RiskRecon's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cybersecurity
- Security Ratings
- Third-Party Risk Management
- Supply Chain Risk
- Risk Management
- GRC
- Vendor Monitoring
- Attack Surface
---
