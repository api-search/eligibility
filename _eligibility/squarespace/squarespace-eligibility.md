---
api_specs:
- filename: squarespace-orders-api-openapi.yml
  format: yaml
  label: Squarespace Orders API
  slug: squarespace-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/squarespace/openapi/squarespace-orders-api-openapi.yml
- filename: squarespace-products-api-openapi.yml
  format: yaml
  label: Squarespace Products API
  slug: squarespace-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/squarespace/openapi/squarespace-products-api-openapi.yml
- filename: squarespace-inventory-api-openapi.yml
  format: yaml
  label: Squarespace Inventory API
  slug: squarespace-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/squarespace/openapi/squarespace-inventory-api-openapi.yml
- filename: squarespace-profiles-api-openapi.yml
  format: yaml
  label: Squarespace Profiles API
  slug: squarespace-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/squarespace/openapi/squarespace-profiles-api-openapi.yml
- filename: squarespace-transactions-api-openapi.yml
  format: yaml
  label: Squarespace Transactions API
  slug: squarespace-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/squarespace/openapi/squarespace-transactions-api-openapi.yml
- filename: squarespace-webhook-subscriptions-api-openapi.yml
  format: yaml
  label: Squarespace Webhook Subscriptions API
  slug: squarespace-webhook-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/squarespace/openapi/squarespace-webhook-subscriptions-api-openapi.yml
- filename: squarespace-site-api-openapi.yml
  format: yaml
  label: Squarespace Site API
  slug: squarespace-site-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/squarespace/openapi/squarespace-site-api-openapi.yml
- filename: squarespace-analytics-api-openapi.yml
  format: yaml
  label: Squarespace Analytics API
  slug: squarespace-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/squarespace/openapi/squarespace-analytics-api-openapi.yml
- filename: squarespace-contacts-api-openapi.yml
  format: yaml
  label: Squarespace Contacts API
  slug: squarespace-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/squarespace/openapi/squarespace-contacts-api-openapi.yml
- filename: squarespace-discounts-api-openapi.yml
  format: yaml
  label: Squarespace Discounts API
  slug: squarespace-discounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/squarespace/openapi/squarespace-discounts-api-openapi.yml
- filename: squarespace-websites-api-openapi.yml
  format: yaml
  label: Squarespace Websites API
  slug: squarespace-websites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/squarespace/openapi/squarespace-websites-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you're using the Services for or on behalf of an organization, you're agreeing to this Agreement on behalf of that organization
    type: business
  minimum_age:
    text: you need to be at least 16 years old to use Squarespace.
    value: '16'
  restricted_uses:
  - summary: Industry-specific regulations
    text: You are not permitted to use the Services in any way that would subject Squarespace to an Industry-Specific Regulation without obtaining Squarespace’s prior written agreement.
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
name: Squarespace
provenance_date: '2026-11-10'
provider_name: Squarespace
provider_slug: squarespace
slug: squarespace-eligibility
source_date: '2026-11-10'
source_filename: squarespace-eligibility.yml
source_heading: Eligibility
source_page: https://www.squarespace.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Squarespace\naid: squarespace\nurl: https://www.squarespace.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you're using the Services for or on behalf of an organization, you're agreeing to this Agreement on behalf\n    of that organization\nrestricted_uses:\n- summary: Industry-specific regulations\n  text: You are not permitted to use the Services in any way that would subject Squarespace to an Industry-Specific\n    Regulation without obtaining Squarespace’s prior written agreement.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: you need to be at least 16 years old to use Squarespace.\n"
source_yaml_url: https://artifacts.apis.io/squarespace/eligibility/squarespace-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Squarespace's own page on 2026-11-10.
synthetic: false
tags:
- Commerce
- E-Commerce
- Marketing
- Payments
- Retail
- Website Builder
- Webhook
---
