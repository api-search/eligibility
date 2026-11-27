---
api_specs:
- filename: mystars-mystars-faas-fulfilment-api-api-openapi.yml
  format: yaml
  label: MyStars FaaS MyStars FaaS — Fulfilment API
  slug: mystars-mystars-faas-fulfilment-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mystars/openapi/mystars-mystars-faas-fulfilment-api-api-openapi.yml
- filename: mystars-orders-api-openapi.yml
  format: yaml
  label: MyStars FaaS Orders API
  slug: mystars-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mystars/openapi/mystars-orders-api-openapi.yml
- filename: mystars-pricing-api-openapi.yml
  format: yaml
  label: MyStars FaaS Pricing API
  slug: mystars-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mystars/openapi/mystars-pricing-api-openapi.yml
- filename: mystars-recipients-api-openapi.yml
  format: yaml
  label: MyStars FaaS Recipients API
  slug: mystars-recipients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mystars/openapi/mystars-recipients-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not located in, ordinarily resident in, or accessing the Platform from a Restricted Jurisdiction
  minimum_age:
    text: You must be at least 18 years old to use the Platform.
    value: '18'
  restricted_uses:
  - summary: Sanctioned jurisdictions and persons
    text: you are not located in, ordinarily resident in, or accessing the Platform from a Restricted Jurisdiction
  - summary: Designated persons
    text: you are not a Designated Person
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
name: MyStars FaaS
provenance_date: '2026-11-10'
provider_name: MyStars FaaS
provider_slug: mystars
slug: mystars-eligibility
source_date: '2026-11-10'
source_filename: mystars-eligibility.yml
source_heading: Eligibility
source_page: https://mystars.tg/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MyStars FaaS\naid: mystars\nurl: https://mystars.tg/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are not located in, ordinarily resident in, or accessing the Platform from a Restricted Jurisdiction\nentity_types: []\nrestricted_uses:\n- summary: Sanctioned jurisdictions and persons\n  text: you are not located in, ordinarily resident in, or accessing the Platform from a Restricted Jurisdiction\n- summary: Designated persons\n  text: you are not a Designated Person\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '18'\n  text: You must be at least 18 years old to use the Platform.\n"
source_yaml_url: https://artifacts.apis.io/mystars/eligibility/mystars-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from MyStars FaaS's own page on 2026-11-10.
synthetic: false
tags:
- Telegram
- telegram-stars
- telegram-premium
- Payments
- Cryptocurrency
- TON
- Fulfilment
- Blockchain
- Digital Goods
- reseller-api
---
