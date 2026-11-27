---
api_specs:
- filename: florist-one-affiliate-api-openapi.yml
  format: yaml
  label: Florist One Affiliate API
  slug: florist-one-affiliate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/florist-one/openapi/florist-one-affiliate-api-openapi.yml
- filename: florist-one-flowershop-api-openapi.yml
  format: yaml
  label: Florist One FlowerShop API
  slug: florist-one-flowershop-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/florist-one/openapi/florist-one-flowershop-api-openapi.yml
- filename: florist-one-giftbaskets-api-openapi.yml
  format: yaml
  label: Florist One GiftBaskets API
  slug: florist-one-giftbaskets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/florist-one/openapi/florist-one-giftbaskets-api-openapi.yml
- filename: florist-one-shopping-cart-api-openapi.yml
  format: yaml
  label: Florist One Shopping Cart API
  slug: florist-one-shopping-cart-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/florist-one/openapi/florist-one-shopping-cart-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: At present, flower delivery is available only for the United States and Canada.
  entity_types:
  - text: If you have registered as or on behalf of an entity, such as a corporation, partnership, limited liability company or other entity, then “Company” refers to the entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No false local florist websites
    text: Company may not make available any website or application that falsely appears to be that of a local florist
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
name: Florist One
provenance_date: '2026-11-09'
provider_name: Florist One
provider_slug: florist-one
slug: florist-one-eligibility
source_date: '2026-11-09'
source_filename: florist-one-eligibility.yml
source_heading: Eligibility
source_page: https://www.floristone.com/api/print_api_legal/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Florist One\naid: florist-one\nurl: https://www.floristone.com/api/print_api_legal/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: At present, flower delivery is available only for the United States and Canada.\nentity_types:\n- type: business\n  text: If you have registered as or on behalf of an entity, such as a corporation, partnership, limited liability\n    company or other entity, then “Company” refers to the entity\nrestricted_uses:\n- summary: No false local florist websites\n  text: Company may not make available any website or application that falsely appears\
  \ to be that of a local florist\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/florist-one/eligibility/florist-one-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Florist One's own page on 2026-11-09.
synthetic: false
tags:
- Delivery
- E-Commerce
- Florists
- Flowers
- Gifts
---
