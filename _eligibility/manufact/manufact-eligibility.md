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
  - summary: Illegal or unauthorized purpose
    text: Use the Service for any illegal or unauthorized purpose
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
name: Manufact (formerly mcp-use)
provenance_date: '2026-11-10'
provider_name: Manufact (formerly mcp-use)
provider_slug: manufact
slug: manufact-eligibility
source_date: '2026-11-10'
source_filename: manufact-eligibility.yml
source_heading: Eligibility
source_page: https://manufact.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Manufact (formerly mcp-use)\naid: manufact\nurl: https://manufact.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or unauthorized purpose\n  text: Use the Service for any illegal or unauthorized purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/manufact/eligibility/manufact-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Manufact (formerly mcp-use)'s own page on 2026-11-10.
synthetic: false
tags:
- Company
- Manufacturing
- Data
- Supply Chain
---
