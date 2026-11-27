---
api_specs:
- filename: extend-claims-management-api-openapi.yml
  format: yaml
  label: Extend Claims Management API
  slug: extend-claims-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/extend/openapi/extend-claims-management-api-openapi.yml
- filename: extend-contracts-api-openapi.yml
  format: yaml
  label: Extend Contracts API
  slug: extend-contracts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/extend/openapi/extend-contracts-api-openapi.yml
- filename: extend-leads-api-openapi.yml
  format: yaml
  label: Extend Leads API
  slug: extend-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/extend/openapi/extend-leads-api-openapi.yml
- filename: extend-offers-api-openapi.yml
  format: yaml
  label: Extend Offers API
  slug: extend-offers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/extend/openapi/extend-offers-api-openapi.yml
- filename: extend-orders-api-openapi.yml
  format: yaml
  label: Extend Orders API
  slug: extend-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/extend/openapi/extend-orders-api-openapi.yml
- filename: extend-products-api-openapi.yml
  format: yaml
  label: Extend Products API
  slug: extend-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/extend/openapi/extend-products-api-openapi.yml
- filename: extend-refunds-api-openapi.yml
  format: yaml
  label: Extend Refunds API
  slug: extend-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/extend/openapi/extend-refunds-api-openapi.yml
- filename: extend-service-orders-api-openapi.yml
  format: yaml
  label: Extend Service Orders API
  slug: extend-service-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/extend/openapi/extend-service-orders-api-openapi.yml
- filename: extend-dynamic-return-policy-api-openapi.yml
  format: yaml
  label: Extend Dynamic Return Policy API
  slug: extend-dynamic-return-policy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/extend/openapi/extend-dynamic-return-policy-api-openapi.yml
- filename: extend-line-items-api-openapi.yml
  format: yaml
  label: Extend Line Items API
  slug: extend-line-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/extend/openapi/extend-line-items-api-openapi.yml
- filename: extend-shippingoffers-api-openapi.yml
  format: yaml
  label: Extend Shipping Offers API
  slug: extend-shippingoffers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/extend/openapi/extend-shippingoffers-api-openapi.yml
- filename: extend-webhooks-api-openapi.yml
  format: yaml
  label: Extend Webhooks API
  slug: extend-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/extend/openapi/extend-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Site is controlled, operated and administered by Extend from its offices within the United States. Reference to services and content on the Site do not imply that such services are available in your local jurisdiction.
  entity_types:
  - text: You represent that you are at least 18 years of age (or the age of majority in the state in which you reside).
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Automated access not provided by Extend
    text: uses any robot, spider, scraper or other automated means or interface not provided by Extend to access the Site;
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
name: Extend
provenance_date: '2026-11-09'
provider_name: Extend
provider_slug: extend
slug: extend-eligibility
source_date: '2026-11-09'
source_filename: extend-eligibility.yml
source_heading: Eligibility
source_page: https://www.extend.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Extend\naid: extend\nurl: https://www.extend.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Site is controlled, operated and administered by Extend from its offices within the United States. Reference\n    to services and content on the Site do not imply that such services are available in your local jurisdiction.\nentity_types:\n- type: individual\n  text: You represent that you are at least 18 years of age (or the age of majority in the state in which you reside).\nrestricted_uses:\n- summary: Automated access not provided by Extend\n  text: uses any robot, spider,\
  \ scraper or other automated means or interface not provided by Extend to access the\n    Site;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/extend/eligibility/extend-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Extend's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Product Protection
- Extended Warranty
- Shipping Protection
- E-Commerce
- Warranty
- Claims
- Contracts
- Retail
- Insurance
---
