---
api_specs:
- filename: commoditypriceapi-commoditypriceapi-api-api-openapi.yml
  format: yaml
  label: CommodityPriceAPI CommodityPriceAPI API
  slug: commoditypriceapi-commoditypriceapi-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commoditypriceapi/openapi/commoditypriceapi-commoditypriceapi-api-api-openapi.yml
- filename: commoditypriceapi-rates-api-openapi.yml
  format: yaml
  label: CommodityPriceAPI Rates API
  slug: commoditypriceapi-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commoditypriceapi/openapi/commoditypriceapi-rates-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is intended for business and professional use and is not directed at children.
    type: business
  - text: These Terms form a binding agreement between you (whether acting personally or on behalf of an organisation)
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful use
    text: You may not use the Service for any unlawful purpose or in breach of any law applicable to you.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must sign up with a genuine company or personal email address.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CommodityPriceAPI
provenance_date: '2026-11-09'
provider_name: CommodityPriceAPI
provider_slug: commoditypriceapi
slug: commoditypriceapi-eligibility
source_date: '2026-11-09'
source_filename: commoditypriceapi-eligibility.yml
source_heading: Eligibility
source_page: https://commoditypriceapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CommodityPriceAPI\naid: commoditypriceapi\nurl: https://commoditypriceapi.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is intended for business and professional use and is not directed at children.\n- type: individual\n  text: These Terms form a binding agreement between you (whether acting personally or on behalf of an organisation)\nrestricted_uses:\n- summary: Unlawful use\n  text: You may not use the Service for any unlawful purpose or in breach of any law applicable to you.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: You must sign up with a genuine company or personal email address.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/commoditypriceapi/eligibility/commoditypriceapi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from CommodityPriceAPI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Commodities
- Finance
- Real-Time
---
