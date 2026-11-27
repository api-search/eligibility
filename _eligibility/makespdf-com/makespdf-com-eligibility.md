---
api_specs:
- filename: makespdf-com-artifacts-api-openapi.yml
  format: yaml
  label: makespdf-com Artifacts API
  slug: makespdf-com-artifacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/makespdf-com/openapi/makespdf-com-artifacts-api-openapi.yml
- filename: makespdf-com-public-api-openapi.yml
  format: yaml
  label: makespdf-com Public API
  slug: makespdf-com-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/makespdf-com/openapi/makespdf-com-public-api-openapi.yml
- filename: makespdf-com-render-api-openapi.yml
  format: yaml
  label: makespdf-com Render API
  slug: makespdf-com-render-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/makespdf-com/openapi/makespdf-com-render-api-openapi.yml
- filename: makespdf-com-validate-api-openapi.yml
  format: yaml
  label: makespdf-com Validate API
  slug: makespdf-com-validate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/makespdf-com/openapi/makespdf-com-validate-api-openapi.yml
- filename: makespdf-com-x402-api-openapi.yml
  format: yaml
  label: makespdf-com X402 API
  slug: makespdf-com-x402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/makespdf-com/openapi/makespdf-com-x402-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 16 years old (or the minimum age required to consent to online services in your jurisdiction, if higher) to create an account.
    value: '16'
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
name: makespdf-com
provenance_date: '2026-11-10'
provider_name: makespdf-com
provider_slug: makespdf-com
slug: makespdf-com-eligibility
source_date: '2026-11-10'
source_filename: makespdf-com-eligibility.yml
source_heading: Eligibility
source_page: https://makespdf.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: makespdf-com\naid: makespdf-com\nurl: https://makespdf.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old (or the minimum age required to consent to online services in your jurisdiction,\n    if higher) to create an account.\n"
source_yaml_url: https://artifacts.apis.io/makespdf-com/eligibility/makespdf-com-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from makespdf-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- PDF
- Conversion
- Developers
---
