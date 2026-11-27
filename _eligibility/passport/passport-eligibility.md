---
api_specs:
- filename: passport-cart-api-openapi.yml
  format: yaml
  label: Passport Cart API
  slug: passport-cart-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/passport/openapi/passport-cart-api-openapi.yml
- filename: passport-order-api-openapi.yml
  format: yaml
  label: Passport Order API
  slug: passport-order-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/passport/openapi/passport-order-api-openapi.yml
- filename: passport-product-price-api-openapi.yml
  format: yaml
  label: Passport Product Price API
  slug: passport-product-price-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/passport/openapi/passport-product-price-api-openapi.yml
- filename: passport-rate-api-openapi.yml
  format: yaml
  label: Passport Rate API
  slug: passport-rate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/passport/openapi/passport-rate-api-openapi.yml
- filename: passport-ship-api-openapi.yml
  format: yaml
  label: Passport Ship API
  slug: passport-ship-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/passport/openapi/passport-ship-api-openapi.yml
- filename: passport-tax-and-duty-api-openapi.yml
  format: yaml
  label: Passport Tax And Duty API
  slug: passport-tax-and-duty-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/passport/openapi/passport-tax-and-duty-api-openapi.yml
- filename: passport-void-api-openapi.yml
  format: yaml
  label: Passport Void API
  slug: passport-void-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/passport/openapi/passport-void-api-openapi.yml
- filename: passport-health-check-api-openapi.yml
  format: yaml
  label: Passport Health Check API
  slug: passport-health-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/passport/openapi/passport-health-check-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: The Site is intended for users who are at least eighteen (18) years old.
    value: '18'
  restricted_uses:
  - summary: Persons barred from receiving services
    text: are not a person barred from receiving services under the laws of the United States or other applicable jurisdiction.
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
name: Passport
provenance_date: '2026-11-10'
provider_name: Passport
provider_slug: passport
slug: passport-eligibility
source_date: '2026-11-10'
source_filename: passport-eligibility.yml
source_heading: Eligibility
source_page: https://passportglobal.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Passport\naid: passport\nurl: https://passportglobal.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Persons barred from receiving services\n  text: are not a person barred from receiving services under the laws of the United States or other applicable\n    jurisdiction.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is intended for users who are at least eighteen (18) years old.\n"
source_yaml_url: https://artifacts.apis.io/passport/eligibility/passport-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Passport's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Shipping
- Logistics
- Cross-border eCommerce
- International Shipping
- Customs Compliance
- Landed Cost
- duties-and-taxes
- Parcel Delivery
- E-Commerce
- Merchant of Record
- Trade Compliance
---
