---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years old and capable of entering into a legally binding agreement to use the Services.
    value: '18'
  restricted_uses:
  - summary: Unlawful purposes
    text: Use the Services for unlawful purposes or in violation of applicable laws and regulations.
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
name: AppGenie
provenance_date: '2026-11-09'
provider_name: AppGenie
provider_slug: appgenie-com-au
slug: appgenie-com-au-eligibility
source_date: '2026-11-09'
source_filename: appgenie-com-au-eligibility.yml
source_heading: Eligibility
source_page: https://appgenie.com.au/Legal/Terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AppGenie\naid: appgenie-com-au\nurl: https://appgenie.com.au/Legal/Terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful purposes\n  text: Use the Services for unlawful purposes or in violation of applicable laws and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and capable of entering into a legally binding agreement to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/appgenie-com-au/eligibility/appgenie-com-au-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from AppGenie's own page on 2026-11-09.
synthetic: false
tags:
- B2B
- Cloud
- Salesforce
- DevSecOps
- Consulting
---
