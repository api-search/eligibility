---
api_specs:
- filename: wsystem-dev-billing-api-openapi.yml
  format: yaml
  label: wsystem-dev Billing API
  slug: wsystem-dev-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wsystem-dev/openapi/wsystem-dev-billing-api-openapi.yml
- filename: wsystem-dev-company-api-openapi.yml
  format: yaml
  label: wsystem-dev Company API
  slug: wsystem-dev-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wsystem-dev/openapi/wsystem-dev-company-api-openapi.yml
- filename: wsystem-dev-e-invoice-api-openapi.yml
  format: yaml
  label: wsystem-dev E Invoice API
  slug: wsystem-dev-e-invoice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wsystem-dev/openapi/wsystem-dev-e-invoice-api-openapi.yml
- filename: wsystem-dev-eori-api-openapi.yml
  format: yaml
  label: wsystem-dev EORI API
  slug: wsystem-dev-eori-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wsystem-dev/openapi/wsystem-dev-eori-api-openapi.yml
- filename: wsystem-dev-health-api-openapi.yml
  format: yaml
  label: wsystem-dev Health API
  slug: wsystem-dev-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wsystem-dev/openapi/wsystem-dev-health-api-openapi.yml
- filename: wsystem-dev-kyb-api-openapi.yml
  format: yaml
  label: wsystem-dev KYB API
  slug: wsystem-dev-kyb-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wsystem-dev/openapi/wsystem-dev-kyb-api-openapi.yml
- filename: wsystem-dev-sanctions-api-openapi.yml
  format: yaml
  label: wsystem-dev Sanctions API
  slug: wsystem-dev-sanctions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wsystem-dev/openapi/wsystem-dev-sanctions-api-openapi.yml
- filename: wsystem-dev-vat-api-openapi.yml
  format: yaml
  label: wsystem-dev VAT API
  slug: wsystem-dev-vat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wsystem-dev/openapi/wsystem-dev-vat-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Paid plans are for businesses only (section 2). You buy a plan for your trade, business or profession, not as a consumer.
    type: business
  - text: If you are a consumer, please use the free tier only.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful UK VAT checks or bulk checks
    text: You must not use the Service to check UK VAT numbers for unlawful purposes or in bulk beyond what you need for your own business checks.
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
name: wsystem-dev
provenance_date: '2026-11-10'
provider_name: wsystem-dev
provider_slug: wsystem-dev
slug: wsystem-dev-eligibility
source_date: '2026-11-10'
source_filename: wsystem-dev-eligibility.yml
source_heading: Eligibility
source_page: https://wsystem.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: wsystem-dev\naid: wsystem-dev\nurl: https://wsystem.dev/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Paid plans are for businesses only (section 2). You buy a plan for your trade, business or profession, not\n    as a consumer.\n- type: individual\n  text: If you are a consumer, please use the free tier only.\nrestricted_uses:\n- summary: Unlawful UK VAT checks or bulk checks\n  text: You must not use the Service to check UK VAT numbers for unlawful purposes or in bulk beyond what you need\n    for your own business checks.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/wsystem-dev/eligibility/wsystem-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from wsystem-dev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Invoicing
- European
- Compliance
---
