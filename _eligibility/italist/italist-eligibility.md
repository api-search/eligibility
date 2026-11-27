---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Services if you are a resident of a country embargoed by the United States, or are a foreign person or entity blocked or denied by the United States government.
  entity_types:
  - text: You may use the Services only as an individual bona fide purchaser.
    type: individual
  - text: You may not use the Services on behalf of any third-party retailer, reseller, brand, corporate user, or the like.
    type: business
  minimum_age:
    text: The Services are available to Members who are 18 years and older
    value: '18'
  restricted_uses:
  - summary: Products not for resale
    text: Any products ordered by you via the Service are for your own private use only and are not for resale.
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
name: Italist
provenance_date: '2026-11-09'
provider_name: Italist
provider_slug: italist
slug: italist-eligibility
source_date: '2026-11-09'
source_filename: italist-eligibility.yml
source_heading: Eligibility
source_page: https://italist.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Italist\naid: italist\nurl: https://italist.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Services if you are a resident of a country embargoed by the United States, or are a\n    foreign person or entity blocked or denied by the United States government.\nentity_types:\n- type: individual\n  text: You may use the Services only as an individual bona fide purchaser.\n- type: business\n  text: You may not use the Services on behalf of any third-party retailer, reseller, brand, corporate user, or\n    the like.\nrestricted_uses:\n\
  - summary: Products not for resale\n  text: Any products ordered by you via the Service are for your own private use only and are not for resale.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are available to Members who are 18 years and older\n"
source_yaml_url: https://artifacts.apis.io/italist/eligibility/italist-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Italist's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Retail
- Fashion
- Luxury
- Marketplace
- Shopify
- Agentic Commerce
- MCP
---
