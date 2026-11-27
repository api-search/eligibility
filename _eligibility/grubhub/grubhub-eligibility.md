---
api_specs:
- filename: grubhub-delivery-quotes-api-openapi.yml
  format: yaml
  label: Grubhub Delivery Quotes API
  slug: grubhub-delivery-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/grubhub/openapi/grubhub-delivery-quotes-api-openapi.yml
- filename: grubhub-delivery-refunds-api-openapi.yml
  format: yaml
  label: Grubhub Delivery Refunds API
  slug: grubhub-delivery-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/grubhub/openapi/grubhub-delivery-refunds-api-openapi.yml
- filename: grubhub-delivery-service-areas-api-openapi.yml
  format: yaml
  label: Grubhub Delivery Service Areas API
  slug: grubhub-delivery-service-areas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/grubhub/openapi/grubhub-delivery-service-areas-api-openapi.yml
- filename: grubhub-delivery-status-api-openapi.yml
  format: yaml
  label: Grubhub Delivery Status API
  slug: grubhub-delivery-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/grubhub/openapi/grubhub-delivery-status-api-openapi.yml
- filename: grubhub-delivery-tests-api-openapi.yml
  format: yaml
  label: Grubhub Delivery Tests API
  slug: grubhub-delivery-tests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/grubhub/openapi/grubhub-delivery-tests-api-openapi.yml
- filename: grubhub-delivery-updates-api-openapi.yml
  format: yaml
  label: Grubhub Delivery Updates API
  slug: grubhub-delivery-updates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/grubhub/openapi/grubhub-delivery-updates-api-openapi.yml
- filename: grubhub-delivery-webhooks-emulation-api-openapi.yml
  format: yaml
  label: Grubhub Delivery Webhooks Emulation API
  slug: grubhub-delivery-webhooks-emulation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/grubhub/openapi/grubhub-delivery-webhooks-emulation-api-openapi.yml
- filename: grubhub-endpoints-api-openapi.yml
  format: yaml
  label: Grubhub Endpoints API
  slug: grubhub-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/grubhub/openapi/grubhub-endpoints-api-openapi.yml
- filename: grubhub-requesting-reports-api-openapi.yml
  format: yaml
  label: Grubhub Requesting Reports API
  slug: grubhub-requesting-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/grubhub/openapi/grubhub-requesting-reports-api-openapi.yml
- filename: grubhub-webhooks-api-openapi.yml
  format: yaml
  label: Grubhub Webhooks API
  slug: grubhub-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/grubhub/openapi/grubhub-webhooks-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: cities throughout the United States and other territories where Grubhub provides such Services
  entity_types:
  - text: Unless otherwise agreed by Grubhub in a separate written agreement with you or your authorized representative, the Platform is made available solely for your personal, non-commercial use.
    type: individual
  - text: You may have another Account if you are using the Platform for business purposes, including as part of an enterprise Account, pursuant to a separate agreement with Grubhub.
    type: business
  minimum_age:
    text: you are not authorized to use the Platform or otherwise access the Services if you are under the age of 16.
    value: '16'
  restricted_uses:
  - summary: Alcohol orders require age 21 or over
    text: you represent and warrant that you are at least 21 years of age.
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
name: Grubhub
provenance_date: '2026-11-09'
provider_name: Grubhub
provider_slug: grubhub
slug: grubhub-eligibility
source_date: '2026-11-09'
source_filename: grubhub-eligibility.yml
source_heading: Eligibility
source_page: https://www.grubhub.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Grubhub\naid: grubhub\nurl: https://www.grubhub.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: cities throughout the United States and other territories where Grubhub provides such Services\nentity_types:\n- type: individual\n  text: Unless otherwise agreed by Grubhub in a separate written agreement with you or your authorized representative,\n    the Platform is made available solely for your personal, non-commercial use.\n- type: business\n  text: You may have another Account if you are using the Platform for business purposes, including\
  \ as part of an\n    enterprise Account, pursuant to a separate agreement with Grubhub.\nrestricted_uses:\n- summary: Alcohol orders require age 21 or over\n  text: you represent and warrant that you are at least 21 years of age.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: you are not authorized to use the Platform or otherwise access the Services if you are under the age of\n    16.\n"
source_yaml_url: https://artifacts.apis.io/grubhub/eligibility/grubhub-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Grubhub's own page on 2026-11-09.
synthetic: false
tags:
- Food Delivery
- Restaurant
- Marketplace
- Online Ordering
- Point-of-Sale
- Logistics
- Last Mile Delivery
- Menu Management
- Hospitality
- Local Commerce
- Delivery
---
