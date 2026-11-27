---
api_specs:
- filename: llcdrop-account-api-openapi.yml
  format: yaml
  label: LLCDrop Account API
  slug: llcdrop-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llcdrop/openapi/llcdrop-account-api-openapi.yml
- filename: llcdrop-businesses-api-openapi.yml
  format: yaml
  label: LLCDrop Businesses API
  slug: llcdrop-businesses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llcdrop/openapi/llcdrop-businesses-api-openapi.yml
- filename: llcdrop-counties-and-stats-api-openapi.yml
  format: yaml
  label: LLCDrop Counties and stats API
  slug: llcdrop-counties-and-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llcdrop/openapi/llcdrop-counties-and-stats-api-openapi.yml
- filename: llcdrop-datasets-api-openapi.yml
  format: yaml
  label: LLCDrop Datasets API
  slug: llcdrop-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llcdrop/openapi/llcdrop-datasets-api-openapi.yml
- filename: llcdrop-filings-api-openapi.yml
  format: yaml
  label: LLCDrop Filings API
  slug: llcdrop-filings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llcdrop/openapi/llcdrop-filings-api-openapi.yml
- filename: llcdrop-parcels-api-openapi.yml
  format: yaml
  label: LLCDrop Parcels API
  slug: llcdrop-parcels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llcdrop/openapi/llcdrop-parcels-api-openapi.yml
- filename: llcdrop-reference-lists-api-openapi.yml
  format: yaml
  label: LLCDrop Reference lists API
  slug: llcdrop-reference-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llcdrop/openapi/llcdrop-reference-lists-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is designed for business and professional use. By using it, you confirm that you are acting for purposes related to your trade, business, craft or profession and not as a consumer, except when you buy an Owner Report, which you may buy as a consumer.
    type: business
  minimum_age:
    text: be at least 18 years old and old enough to form a binding contract where you live
    value: '18'
  restricted_uses:
  - summary: No FCRA purposes for Lead Data
    text: 'You will not use Lead Data, or any information derived from it, in whole or in part, as a factor in establishing any individual''s eligibility for: credit or insurance'
  - summary: No FCRA purposes for Owner Reports
    text: You must not use an Owner Report, or any information from it, in whole or in part, as a factor in deciding any person's eligibility for employment
  - summary: No stalking, harassment or debt collection with Owner Reports
    text: You must not use it for any prohibited use listed below, including to locate, stalk, harass, threaten or intimidate anyone; to collect a consumer debt
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
name: LLCDrop
provenance_date: '2026-11-09'
provider_name: LLCDrop
provider_slug: llcdrop
slug: llcdrop-eligibility
source_date: '2026-11-09'
source_filename: llcdrop-eligibility.yml
source_heading: Eligibility
source_page: https://llcdrop.com/marketing/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LLCDrop\naid: llcdrop\nurl: https://llcdrop.com/marketing/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is designed for business and professional use. By using it, you confirm that you are acting\n    for purposes related to your trade, business, craft or profession and not as a consumer, except when you buy\n    an Owner Report, which you may buy as a consumer.\nrestricted_uses:\n- summary: No FCRA purposes for Lead Data\n  text: 'You will not use Lead Data, or any information derived from it, in whole or in\
  \ part, as a factor in establishing\n    any individual''s eligibility for: credit or insurance'\n- summary: No FCRA purposes for Owner Reports\n  text: You must not use an Owner Report, or any information from it, in whole or in part, as a factor in deciding\n    any person's eligibility for employment\n- summary: No stalking, harassment or debt collection with Owner Reports\n  text: You must not use it for any prohibited use listed below, including to locate, stalk, harass, threaten or\n    intimidate anyone; to collect a consumer debt\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: be at least 18 years old and old enough to form a binding contract where you live\n"
source_yaml_url: https://artifacts.apis.io/llcdrop/eligibility/llcdrop-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from LLCDrop's own page on 2026-11-09.
synthetic: false
tags:
- Lead Generation
- Business Data
- Marketing
- Real Estate
---
