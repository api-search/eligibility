---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Not all products and services we offer may be available in each of the locations where we do business.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No personal advice reliance
    text: nothing on this Web site is intended to provide personal financial, tax or legal advice.
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
name: UMB Bank
provenance_date: '2026-11-10'
provider_name: UMB Bank
provider_slug: umb-financial
slug: umb-financial-eligibility
source_date: '2026-11-10'
source_filename: umb-financial-eligibility.yml
source_heading: Eligibility
source_page: https://www.umb.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: UMB Bank\naid: umb-financial\nurl: https://www.umb.com/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Not all products and services we offer may be available in each of the locations where we do business.\nentity_types: []\nrestricted_uses:\n- summary: No personal advice reliance\n  text: nothing on this Web site is intended to provide personal financial, tax or legal advice.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/umb-financial/eligibility/umb-financial-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from UMB Bank's own page on 2026-11-10.
synthetic: false
tags:
- Financial Services
- Banking
- United States
- Open Finance
- Banking as a Service
- Institutional Banking
---
