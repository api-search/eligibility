---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We currently offer products and services for the United States market only.
  entity_types:
  - text: This site is intended for a business audience. Our products and services are marketed to businesses and not for any individual or household use.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Individual or household use
    text: Our products and services are marketed to businesses and not for any individual or household use.
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
name: Skeps
provenance_date: '2026-11-10'
provider_name: Skeps
provider_slug: skeps
slug: skeps-eligibility
source_date: '2026-11-10'
source_filename: skeps-eligibility.yml
source_heading: Eligibility
source_page: https://www.skeps.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Skeps\naid: skeps\nurl: https://www.skeps.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We currently offer products and services for the United States market only.\nentity_types:\n- type: business\n  text: This site is intended for a business audience. Our products and services are marketed to businesses and\n    not for any individual or household use.\nrestricted_uses:\n- summary: Individual or household use\n  text: Our products and services are marketed to businesses and not for any individual or household use.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/skeps/eligibility/skeps-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Skeps's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Fintech
- Embedded Finance
- Lending
- Point-of-Sale
- Pay Over Time
- Buy Now Pay Later
- Payments
---
