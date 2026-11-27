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
  - summary: Harvesting others' information
    text: Harvest or otherwise collect information about others, including e-mail addresses, without their consent.
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
name: Argus Investor
provenance_date: '2026-11-09'
provider_name: Argus Investor
provider_slug: argus-investor
slug: argus-investor-eligibility
source_date: '2026-11-09'
source_filename: argus-investor-eligibility.yml
source_heading: Eligibility
source_page: https://www.argusresearch.com/terms.aspx
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Argus Investor\naid: argus-investor\nurl: https://www.argusresearch.com/terms.aspx\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Harvesting others' information\n  text: Harvest or otherwise collect information about others, including e-mail addresses, without their consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/argus-investor/eligibility/argus-investor-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Argus Investor's own page on 2026-11-09.
synthetic: false
tags:
- Equity Analysis
- Financial Data
- Financial Services
- Investment Ratings
- Stock Research
---
