---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided when using the Services is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: whether personally or on behalf of an entity ("you")
    type: individual
  - text: whether personally or on behalf of an entity ("you")
    type: business
  minimum_age:
    text: The Services are intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Protected Health Information
    text: Customer may use the Services to create, receive, maintain, or transmit Protected Health Information ("PHI") only if Customer and Company have executed a Business Associate Agreement ("BAA") governing such use.
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
name: Greybeam
provenance_date: '2026-11-09'
provider_name: Greybeam
provider_slug: greybeam
slug: greybeam-eligibility
source_date: '2026-11-09'
source_filename: greybeam-eligibility.yml
source_heading: Eligibility
source_page: https://www.greybeam.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Greybeam\naid: greybeam\nurl: https://www.greybeam.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided when using the Services is not intended for distribution to or use by any person\n    or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: whether personally or on behalf of an entity (\"you\")\n- type: business\n  text: whether personally or on behalf of an entity (\"you\")\nrestricted_uses:\n- summary: Protected Health Information\n  text: Customer\
  \ may use the Services to create, receive, maintain, or transmit Protected Health Information (\"PHI\")\n    only if Customer and Company have executed a Business Associate Agreement (\"BAA\") governing such use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/greybeam/eligibility/greybeam-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Greybeam's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Snowflake
- DuckDB
- Cost Optimization
- Data Engineering
---
