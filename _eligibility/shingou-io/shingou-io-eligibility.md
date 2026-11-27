---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and legally able to enter into a contract.
    type: individual
  - text: If you use the Service on behalf of an organisation, you confirm you are authorised to bind that organisation.
    type: business
  minimum_age:
    text: You must be at least 18 years old and legally able to enter into a contract.
    value: '18'
  restricted_uses:
  - summary: Free tier limited to non-commercial use
    text: The Free tier may not be used to operate a commercial product or service, to trade or manage assets on behalf of third parties, or otherwise to generate revenue.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Sign-in uses a one-time email link
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: shingou-io
provenance_date: '2026-11-10'
provider_name: shingou-io
provider_slug: shingou-io
slug: shingou-io-eligibility
source_date: '2026-11-10'
source_filename: shingou-io-eligibility.yml
source_heading: Eligibility
source_page: https://shingou.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: shingou-io\naid: shingou-io\nurl: https://shingou.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and legally able to enter into a contract.\n- type: business\n  text: If you use the Service on behalf of an organisation, you confirm you are authorised to bind that organisation.\nrestricted_uses:\n- summary: Free tier limited to non-commercial use\n  text: The Free tier may not be used to operate a commercial product or service, to trade or manage assets on behalf\n    of third parties, or\
  \ otherwise to generate revenue.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Sign-in uses a one-time email link\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally able to enter into a contract.\n"
source_yaml_url: https://artifacts.apis.io/shingou-io/eligibility/shingou-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from shingou-io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cryptocurrency
- Sentiment
- Data
---
