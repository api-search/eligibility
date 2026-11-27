---
api_specs:
- filename: bungalow-applications-api-openapi.yml
  format: yaml
  label: Bungalow Applications API
  slug: bungalow-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bungalow/openapi/bungalow-applications-api-openapi.yml
- filename: bungalow-listings-api-openapi.yml
  format: yaml
  label: Bungalow Listings API
  slug: bungalow-listings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bungalow/openapi/bungalow-listings-api-openapi.yml
- filename: bungalow-markets-api-openapi.yml
  format: yaml
  label: Bungalow Markets API
  slug: bungalow-markets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bungalow/openapi/bungalow-markets-api-openapi.yml
- filename: bungalow-showings-api-openapi.yml
  format: yaml
  label: Bungalow Showings API
  slug: bungalow-showings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bungalow/openapi/bungalow-showings-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You represent and warrant that you are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Under-18 users barred
    text: If you are under age 18, you may not, under any circumstances or for any reason, use the Services.
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
name: Bungalow
provenance_date: '2026-11-09'
provider_name: Bungalow
provider_slug: bungalow
slug: bungalow-eligibility
source_date: '2026-11-09'
source_filename: bungalow-eligibility.yml
source_heading: Eligibility
source_page: https://bungalow.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bungalow\naid: bungalow\nurl: https://bungalow.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Under-18 users barred\n  text: If you are under age 18, you may not, under any circumstances or for any reason, use the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/bungalow/eligibility/bungalow-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Bungalow's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- Residential Real Estate
- Rental Listings
- Property Management
- Co-Living
- Single-Family Rental
- Listings Syndication
- Housing
- PropTech
- Marketplace
---
