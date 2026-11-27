---
api_specs:
- filename: evidinvest-com-calculations-api-openapi.yml
  format: yaml
  label: evidinvest-com Calculations API
  slug: evidinvest-com-calculations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evidinvest-com/openapi/evidinvest-com-calculations-api-openapi.yml
- filename: evidinvest-com-financial-data-api-openapi.yml
  format: yaml
  label: evidinvest-com Financial Data API
  slug: evidinvest-com-financial-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evidinvest-com/openapi/evidinvest-com-financial-data-api-openapi.yml
- filename: evidinvest-com-machine-payments-api-openapi.yml
  format: yaml
  label: evidinvest-com Machine Payments API
  slug: evidinvest-com-machine-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evidinvest-com/openapi/evidinvest-com-machine-payments-api-openapi.yml
- filename: evidinvest-com-market-data-api-openapi.yml
  format: yaml
  label: evidinvest-com Market Data API
  slug: evidinvest-com-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evidinvest-com/openapi/evidinvest-com-market-data-api-openapi.yml
- filename: evidinvest-com-portfolio-api-openapi.yml
  format: yaml
  label: evidinvest-com Portfolio API
  slug: evidinvest-com-portfolio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evidinvest-com/openapi/evidinvest-com-portfolio-api-openapi.yml
- filename: evidinvest-com-sec-filings-api-openapi.yml
  format: yaml
  label: evidinvest-com SEC Filings API
  slug: evidinvest-com-sec-filings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evidinvest-com/openapi/evidinvest-com-sec-filings-api-openapi.yml
- filename: evidinvest-com-user-lists-api-openapi.yml
  format: yaml
  label: evidinvest-com User Lists API
  slug: evidinvest-com-user-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evidinvest-com/openapi/evidinvest-com-user-lists-api-openapi.yml
- filename: evidinvest-com-valuation-api-openapi.yml
  format: yaml
  label: evidinvest-com Valuation API
  slug: evidinvest-com-valuation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evidinvest-com/openapi/evidinvest-com-valuation-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and legally capable of entering into a binding agreement to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Investment advice reliance
    text: You must not rely on the Service as the sole basis for any investment, trading, business, or financial decision.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may need an account to access parts of the Service.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: evidinvest-com
provenance_date: '2026-11-09'
provider_name: evidinvest-com
provider_slug: evidinvest-com
slug: evidinvest-com-eligibility
source_date: '2026-11-09'
source_filename: evidinvest-com-eligibility.yml
source_heading: Eligibility
source_page: https://evidinvest.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: evidinvest-com\naid: evidinvest-com\nurl: https://evidinvest.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and legally capable of entering into a binding agreement to use the Service.\nrestricted_uses:\n- summary: Investment advice reliance\n  text: You must not rely on the Service as the sole basis for any investment, trading, business, or financial decision.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may need an account to access parts\
  \ of the Service.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/evidinvest-com/eligibility/evidinvest-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from evidinvest-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Valuation
- Data
---
