---
api_specs:
- filename: brink-commerce-custom-api-openapi.yml
  format: yaml
  label: Brink Commerce Custom API
  slug: brink-commerce-custom-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brink-commerce/openapi/brink-commerce-custom-api-openapi.yml
- filename: brink-commerce-deliveries-api-openapi.yml
  format: yaml
  label: Brink Commerce Deliveries API
  slug: brink-commerce-deliveries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brink-commerce/openapi/brink-commerce-deliveries-api-openapi.yml
- filename: brink-commerce-orders-api-openapi.yml
  format: yaml
  label: Brink Commerce Orders API
  slug: brink-commerce-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brink-commerce/openapi/brink-commerce-orders-api-openapi.yml
- filename: brink-commerce-products-api-openapi.yml
  format: yaml
  label: Brink Commerce Products API
  slug: brink-commerce-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brink-commerce/openapi/brink-commerce-products-api-openapi.yml
- filename: brink-commerce-technical-api-openapi.yml
  format: yaml
  label: Brink Commerce Technical API
  slug: brink-commerce-technical-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brink-commerce/openapi/brink-commerce-technical-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use by third parties restricted
    text: Services may however not be used by consultants, agents, subcontractors, or any third parties without our prior written approval.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Subject to our acceptance/confirmation of a Merchant Agreement, our mutual agreement will become effective
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Brink Commerce
provenance_date: '2026-11-09'
provider_name: Brink Commerce
provider_slug: brink-commerce
slug: brink-commerce-eligibility
source_date: '2026-11-09'
source_filename: brink-commerce-eligibility.yml
source_heading: Eligibility
source_page: https://www.brinkcommerce.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brink Commerce\naid: brink-commerce\nurl: https://www.brinkcommerce.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Use by third parties restricted\n  text: Services may however not be used by consultants, agents, subcontractors, or any third parties without our\n    prior written approval.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Subject to our acceptance/confirmation of a Merchant Agreement, our mutual agreement will become effective\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/brink-commerce/eligibility/brink-commerce-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Brink Commerce's own page on 2026-11-09.
synthetic: false
tags:
- E-Commerce
- Platform
- Enterprise
- Composable
---
