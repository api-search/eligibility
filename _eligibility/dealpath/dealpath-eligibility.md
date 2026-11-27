---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer affirms that it is not named on, owned by, or acting on behalf of any U.S. government denied-party list
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export and sanctions compliance
    text: comply fully with all relevant export control and sanctions laws and regulations of the United States
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
name: Dealpath
provenance_date: '2026-11-09'
provider_name: Dealpath
provider_slug: dealpath
slug: dealpath-eligibility
source_date: '2026-11-09'
source_filename: dealpath-eligibility.yml
source_heading: Eligibility
source_page: https://www.dealpath.com/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dealpath\naid: dealpath\nurl: https://www.dealpath.com/tos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Customer affirms that it is not named on, owned by, or acting on behalf of any U.S. government denied-party\n    list\nentity_types: []\nrestricted_uses:\n- summary: Export and sanctions compliance\n  text: comply fully with all relevant export control and sanctions laws and regulations of the United States\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dealpath/eligibility/dealpath-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Dealpath's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- PropTech
- Deal Management
- Commercial Real Estate
- Investment Management
- Real Estate Technology
---
