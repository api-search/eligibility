---
api_specs:
- filename: duck-creek-billing-api-openapi.yml
  format: yaml
  label: Duck Creek Billing API
  slug: duck-creek-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/duck-creek/openapi/duck-creek-billing-api-openapi.yml
- filename: duck-creek-claims-api-openapi.yml
  format: yaml
  label: Duck Creek Claims API
  slug: duck-creek-claims-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/duck-creek/openapi/duck-creek-claims-api-openapi.yml
- filename: duck-creek-policies-api-openapi.yml
  format: yaml
  label: duck-creek Policies API
  slug: duck-creek-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/duck-creek/openapi/duck-creek-policies-api-openapi.yml
- filename: duck-creek-products-api-openapi.yml
  format: yaml
  label: duck-creek Products API
  slug: duck-creek-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/duck-creek/openapi/duck-creek-products-api-openapi.yml
- filename: duck-creek-quotes-api-openapi.yml
  format: yaml
  label: duck-creek Quotes API
  slug: duck-creek-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/duck-creek/openapi/duck-creek-quotes-api-openapi.yml
claim_count: 1
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
  - summary: Unlawful access or use
    text: You agree that you will not access or use the information on this site in violation of such laws.
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
name: Duck Creek
provenance_date: '2026-11-09'
provider_name: Duck Creek
provider_slug: duck-creek
slug: duck-creek-eligibility
source_date: '2026-11-09'
source_filename: duck-creek-eligibility.yml
source_heading: Eligibility
source_page: https://www.duckcreek.com/duck-creek-terms-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Duck Creek\naid: duck-creek\nurl: https://www.duckcreek.com/duck-creek-terms-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful access or use\n  text: You agree that you will not access or use the information on this site in violation of such laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/duck-creek/eligibility/duck-creek-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Duck Creek's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Payments
- Claims
- Payment Processing
- Product
---
