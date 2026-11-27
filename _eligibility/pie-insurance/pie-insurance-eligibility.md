---
api_specs:
- filename: pie-insurance-appetite-api-openapi.yml
  format: yaml
  label: Pie Insurance Appetite API
  slug: pie-insurance-appetite-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pie-insurance/openapi/pie-insurance-appetite-api-openapi.yml
- filename: pie-insurance-classcodesearch-api-openapi.yml
  format: yaml
  label: Pie Insurance ClassCodeSearch API
  slug: pie-insurance-classcodesearch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pie-insurance/openapi/pie-insurance-classcodesearch-api-openapi.yml
- filename: pie-insurance-eligibility-api-openapi.yml
  format: yaml
  label: Pie Insurance Eligibility API
  slug: pie-insurance-eligibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pie-insurance/openapi/pie-insurance-eligibility-api-openapi.yml
- filename: pie-insurance-priceindication-api-openapi.yml
  format: yaml
  label: Pie Insurance PriceIndication API
  slug: pie-insurance-priceindication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pie-insurance/openapi/pie-insurance-priceindication-api-openapi.yml
- filename: pie-insurance-quotedocument-api-openapi.yml
  format: yaml
  label: Pie Insurance QuoteDocument API
  slug: pie-insurance-quotedocument-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pie-insurance/openapi/pie-insurance-quotedocument-api-openapi.yml
- filename: pie-insurance-quotepdf-api-openapi.yml
  format: yaml
  label: Pie Insurance QuotePdf API
  slug: pie-insurance-quotepdf-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pie-insurance/openapi/pie-insurance-quotepdf-api-openapi.yml
- filename: pie-insurance-quotes-api-openapi.yml
  format: yaml
  label: Pie Insurance Quotes API
  slug: pie-insurance-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pie-insurance/openapi/pie-insurance-quotes-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: none of the features, products, or services are available outside of the United States.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful use prohibited
    text: You may not use the Site or any Content for any purpose that is unlawful or prohibited by these Terms of Use
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
name: Pie Insurance
provenance_date: '2026-11-10'
provider_name: Pie Insurance
provider_slug: pie-insurance
slug: pie-insurance-eligibility
source_date: '2026-11-10'
source_filename: pie-insurance-eligibility.yml
source_heading: Eligibility
source_page: https://www.pieinsurance.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pie Insurance\naid: pie-insurance\nurl: https://www.pieinsurance.com/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: none of the features, products, or services are available outside of the United States.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful use prohibited\n  text: You may not use the Site or any Content for any purpose that is unlawful or prohibited by these Terms of\n    Use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pie-insurance/eligibility/pie-insurance-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Pie Insurance's own page on 2026-11-10.
synthetic: false
tags:
- Insurance
- Insurtech
- Workers Compensation
- Small Business
- Commercial Insurance
- Business Owners Policy
- Commercial Auto
- General Liability
- Professional Liability
- Agency Portal
- Partner API
- Quoting
- Bindings
---
