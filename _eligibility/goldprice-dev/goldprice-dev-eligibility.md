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
  - summary: Sole data source for critical decisions
    text: Do not use the Service as the sole data source for safety-critical, regulatory, or high-value financial decisions without independent verification.
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
name: goldprice-dev
provenance_date: '2026-11-09'
provider_name: goldprice-dev
provider_slug: goldprice-dev
slug: goldprice-dev-eligibility
source_date: '2026-11-09'
source_filename: goldprice-dev-eligibility.yml
source_heading: Eligibility
source_page: https://goldprice.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: goldprice-dev\naid: goldprice-dev\nurl: https://goldprice.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Sole data source for critical decisions\n  text: Do not use the Service as the sole data source for safety-critical, regulatory, or high-value financial\n    decisions without independent verification.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/goldprice-dev/eligibility/goldprice-dev-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from goldprice-dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Commodities
- Data
---
