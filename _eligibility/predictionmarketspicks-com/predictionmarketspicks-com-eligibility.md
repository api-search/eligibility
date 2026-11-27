---
api_specs:
- filename: predictionmarketspicks-com-openapi-generated.yml
  format: yaml
  label: predictionmarketspicks-com API
  slug: predictionmarketspicks-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/predictionmarketspicks-com/openapi/_ae-authored/predictionmarketspicks-com-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Polymarket.com, the international book, is view-only for US users.
  entity_types:
  - text: You must be at least 18 years old to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Unlawful purposes
    text: Use the Service for any unlawful purpose
  - summary: VPN or false location to access offers
    text: Use a VPN, proxy, false location or false information to see or use an offer, or to reach a platform, that isn't available where you are
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
name: predictionmarketspicks-com
provenance_date: '2026-11-10'
provider_name: predictionmarketspicks-com
provider_slug: predictionmarketspicks-com
slug: predictionmarketspicks-com-eligibility
source_date: '2026-11-10'
source_filename: predictionmarketspicks-com-eligibility.yml
source_heading: Eligibility
source_page: https://predictionmarketspicks.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: predictionmarketspicks-com\naid: predictionmarketspicks-com\nurl: https://predictionmarketspicks.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Polymarket.com, the international book, is view-only for US users.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Service.\nrestricted_uses:\n- summary: Unlawful purposes\n  text: Use the Service for any unlawful purpose\n- summary: VPN or false location to access offers\n  text: Use a VPN, proxy, false location or false information to see or use an offer, or to reach a platform, that\n \
  \   isn't available where you are\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/predictionmarketspicks-com/eligibility/predictionmarketspicks-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from predictionmarketspicks-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Prediction Markets
- TradingTools
- Analytics
- News
---
