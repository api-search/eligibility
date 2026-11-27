---
api_specs:
- filename: ibotta-openai-api-openapi.yml
  format: yaml
  label: Ibotta Openai API
  slug: ibotta-openai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibotta/openapi/ibotta-openai-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - PR
    text: You also must be located in the United States or Puerto Rico when using the Services.
  entity_types:
  - text: You must be at least eighteen (18) years old to use the Services
    type: individual
  - text: If you are using the Services on behalf of an entity, organization, or company (collectively "Subscribing Organization"), you represent and warrant to us that you are an authorized representative of that Subscribing Organization
    type: business
  minimum_age:
    text: You must be at least eighteen (18) years old to use the Services
    value: '18'
  restricted_uses:
  - summary: Alcohol offers require age 21
    text: must be at least 21 years old to redeem Offers associated with alcoholic beverages on the Services
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 'You also agree to use one or more of the following multi-factor authentication methods in order to provide further security to your account: (i) phone number, (ii) email address, or (iii) such other methods as may be offered by Ibotta in its sole discretion.'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ibotta
provenance_date: '2026-11-09'
provider_name: Ibotta
provider_slug: ibotta
slug: ibotta-eligibility
source_date: '2026-11-09'
source_filename: ibotta-eligibility.yml
source_heading: Eligibility
source_page: https://legal.ibotta.com/policies
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ibotta\naid: ibotta\nurl: https://legal.ibotta.com/policies\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - PR\n  excluded: []\n  text: You also must be located in the United States or Puerto Rico when using the Services.\nentity_types:\n- type: individual\n  text: You must be at least eighteen (18) years old to use the Services\n- type: business\n  text: If you are using the Services on behalf of an entity, organization, or company (collectively \"Subscribing\n    Organization\"), you represent and warrant to us that you are an authorized representative of that Subscribing\n    Organization\n\
  restricted_uses:\n- summary: Alcohol offers require age 21\n  text: must be at least 21 years old to redeem Offers associated with alcoholic beverages on the Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 'You also agree to use one or more of the following multi-factor authentication methods in order to provide\n    further security to your account: (i) phone number, (ii) email address, or (iii) such other methods as may be\n    offered by Ibotta in its sole discretion.'\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years old to use the Services\n"
source_yaml_url: https://artifacts.apis.io/ibotta/eligibility/ibotta-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Ibotta's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Cashback
- Rewards
- Retail Media
- Coupons
- Loyalty
- Shopping
- Advertising
- Promotions
- Product Search
- Retail
- Affiliates
- Consumer Packaged Goods
---
