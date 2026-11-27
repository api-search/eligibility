---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you are 18 years or older
    value: '18'
  restricted_uses:
  - summary: Export control restrictions
    text: you are not located in, under the control of, or a national or resident of an embargoed country or prohibited end user under Export Laws
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Juniper Square reserves the right to refuse or reject any request to create an account for you for any or no reason at Juniper Square’s sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Juniper Square
provenance_date: '2026-11-09'
provider_name: Juniper Square
provider_slug: junipersquare
slug: junipersquare-eligibility
source_date: '2026-11-09'
source_filename: junipersquare-eligibility.yml
source_heading: Eligibility
source_page: https://www.junipersquare.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Juniper Square\naid: junipersquare\nurl: https://www.junipersquare.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export control restrictions\n  text: you are not located in, under the control of, or a national or resident of an embargoed country or prohibited\n    end user under Export Laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Juniper Square reserves the right to refuse or reject any request to create an account for you for any or\n    no reason at Juniper Square’s sole\
  \ discretion.\nminimum_age:\n  value: '18'\n  text: you are 18 years or older\n"
source_yaml_url: https://artifacts.apis.io/junipersquare/eligibility/junipersquare-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Juniper Square's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Investment Management
- Private Markets
- Fund Administration
- Fund Accounting
- Commercial Real Estate
- Private Equity
- Investor Relations
- MCP
- AI Agents
---
