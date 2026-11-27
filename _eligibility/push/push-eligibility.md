---
api_specs:
- filename: push-account-api-openapi.yml
  format: yaml
  label: Push Account API
  slug: push-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/push/openapi/push-account-api-openapi.yml
- filename: push-audience-list-api-openapi.yml
  format: yaml
  label: Push Audience List API
  slug: push-audience-list-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/push/openapi/push-audience-list-api-openapi.yml
- filename: push-campaigns-api-openapi.yml
  format: yaml
  label: Push Campaigns API
  slug: push-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/push/openapi/push-campaigns-api-openapi.yml
- filename: push-company-api-openapi.yml
  format: yaml
  label: Push Company API
  slug: push-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/push/openapi/push-company-api-openapi.yml
- filename: push-company-custom-fields-api-openapi.yml
  format: yaml
  label: Push Company custom fields API
  slug: push-company-custom-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/push/openapi/push-company-custom-fields-api-openapi.yml
- filename: push-contact-api-openapi.yml
  format: yaml
  label: Push Contact API
  slug: push-contact-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/push/openapi/push-contact-api-openapi.yml
- filename: push-contact-custom-fields-api-openapi.yml
  format: yaml
  label: Push Contact Custom fields API
  slug: push-contact-custom-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/push/openapi/push-contact-custom-fields-api-openapi.yml
- filename: push-coupon-lists-api-openapi.yml
  format: yaml
  label: Push Coupon lists API
  slug: push-coupon-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/push/openapi/push-coupon-lists-api-openapi.yml
- filename: push-deliveries-api-openapi.yml
  format: yaml
  label: Push Deliveries API
  slug: push-deliveries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/push/openapi/push-deliveries-api-openapi.yml
- filename: push-hotel-data-api-openapi.yml
  format: yaml
  label: Push Hotel Data API
  slug: push-hotel-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/push/openapi/push-hotel-data-api-openapi.yml
- filename: push-hotel-data-custom-fields-api-openapi.yml
  format: yaml
  label: Push Hotel Data custom fields API
  slug: push-hotel-data-custom-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/push/openapi/push-hotel-data-custom-fields-api-openapi.yml
- filename: push-product-api-openapi.yml
  format: yaml
  label: Push Product API
  slug: push-product-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/push/openapi/push-product-api-openapi.yml
- filename: push-product-custom-fields-api-openapi.yml
  format: yaml
  label: Push Product custom fields API
  slug: push-product-custom-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/push/openapi/push-product-custom-fields-api-openapi.yml
- filename: push-purchase-api-openapi.yml
  format: yaml
  label: Push Purchase API
  slug: push-purchase-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/push/openapi/push-purchase-api-openapi.yml
- filename: push-sync-data-api-openapi.yml
  format: yaml
  label: Push Sync Data API
  slug: push-sync-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/push/openapi/push-sync-data-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: not stated
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal purposes
    text: You will not use the Service for any illegal purposes, and you will not violate any applicable laws
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
name: Push
provenance_date: '2026-11-10'
provider_name: Push
provider_slug: push
slug: push-eligibility
source_date: '2026-11-10'
source_filename: push-eligibility.yml
source_heading: Eligibility
source_page: https://www.pushtech.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Push\naid: push\nurl: https://www.pushtech.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: not stated\nentity_types: []\nrestricted_uses:\n- summary: Illegal purposes\n  text: You will not use the Service for any illegal purposes, and you will not violate any applicable laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/push/eligibility/push-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Push's own page on 2026-11-10.
synthetic: false
tags:
- Company
- CRM
- Customer Data Platform
- Marketing Automation
- Hospitality
- Hotels
- Guest Experience
- Email
- SMS
- Push Notifications
- Webhook
- Segmentation
---
