---
api_specs:
- filename: distyra-authentication-api-openapi.yml
  format: yaml
  label: Brightfield Software Authentication API
  slug: distyra-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/distyra/openapi/distyra-authentication-api-openapi.yml
- filename: distyra-billing-api-openapi.yml
  format: yaml
  label: Brightfield Software Billing API
  slug: distyra-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/distyra/openapi/distyra-billing-api-openapi.yml
- filename: distyra-catalog-api-openapi.yml
  format: yaml
  label: Brightfield Software Catalog API
  slug: distyra-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/distyra/openapi/distyra-catalog-api-openapi.yml
- filename: distyra-connect-api-openapi.yml
  format: yaml
  label: Brightfield Software Connect API
  slug: distyra-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/distyra/openapi/distyra-connect-api-openapi.yml
- filename: distyra-enrichment-api-openapi.yml
  format: yaml
  label: Brightfield Software Enrichment API
  slug: distyra-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/distyra/openapi/distyra-enrichment-api-openapi.yml
- filename: distyra-feedback-api-openapi.yml
  format: yaml
  label: Brightfield Software Feedback API
  slug: distyra-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/distyra/openapi/distyra-feedback-api-openapi.yml
- filename: distyra-system-api-openapi.yml
  format: yaml
  label: Brightfield Software System API
  slug: distyra-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/distyra/openapi/distyra-system-api-openapi.yml
- filename: distyra-underwriting-api-openapi.yml
  format: yaml
  label: Brightfield Software Underwriting API
  slug: distyra-underwriting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/distyra/openapi/distyra-underwriting-api-openapi.yml
- filename: distyra-webhooks-api-openapi.yml
  format: yaml
  label: Brightfield Software Webhooks API
  slug: distyra-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/distyra/openapi/distyra-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Connect is available in supported markets; see the Connect page for current coverage.
  entity_types:
  - text: the Service is for businesses, sole traders, and other natural persons acting in a business capacity, and is not offered directly to consumers acting outside a trade or profession.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful use
    text: use the Service for any purpose that is unlawful in the European Union or your country of operation.
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
name: Brightfield Software
provenance_date: '2026-11-09'
provider_name: Brightfield Software
provider_slug: distyra
slug: distyra-eligibility
source_date: '2026-11-09'
source_filename: distyra-eligibility.yml
source_heading: Eligibility
source_page: https://www.distyra.eu/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brightfield Software\naid: distyra\nurl: https://www.distyra.eu/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Connect is available in supported markets; see the Connect page for current coverage.\nentity_types:\n- type: business\n  text: the Service is for businesses, sole traders, and other natural persons acting in a business capacity, and\n    is not offered directly to consumers acting outside a trade or profession.\nrestricted_uses:\n- summary: Unlawful use\n  text: use the Service for any purpose that is unlawful in the European Union or your country of operation.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/distyra/eligibility/distyra-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Brightfield Software's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Banking
- Fintech
- European
---
