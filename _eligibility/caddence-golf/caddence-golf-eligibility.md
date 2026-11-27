---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: Caddence aggregates publicly available pricing from UK retailers
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful use
    text: use the service for anything unlawful.
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
name: Caddence
provenance_date: '2026-11-09'
provider_name: Caddence
provider_slug: caddence-golf
slug: caddence-golf-eligibility
source_date: '2026-11-09'
source_filename: caddence-golf-eligibility.yml
source_heading: Eligibility
source_page: https://caddence.golf/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Caddence\naid: caddence-golf\nurl: https://caddence.golf/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: Caddence aggregates publicly available pricing from UK retailers\nentity_types: []\nrestricted_uses:\n- summary: Unlawful use\n  text: use the service for anything unlawful.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/caddence-golf/eligibility/caddence-golf-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Caddence's own page on 2026-11-09.
synthetic: false
tags:
- Golf
- Price Comparison
- Retail
- Data Analytics
- United Kingdom
---
