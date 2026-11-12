---
api_specs:
- filename: coupondroid-it-a2a-api-openapi.yml
  format: yaml
  label: Coupondroid Italia A2a API
  slug: coupondroid-it-a2a-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-it/openapi/coupondroid-it-a2a-api-openapi.yml
- filename: coupondroid-it-auth-md-api-openapi.yml
  format: yaml
  label: Coupondroid Italia Auth.md API
  slug: coupondroid-it-auth-md-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-it/openapi/coupondroid-it-auth-md-api-openapi.yml
- filename: coupondroid-it-llms-txt-api-openapi.yml
  format: yaml
  label: Coupondroid Italia Llms.txt API
  slug: coupondroid-it-llms-txt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-it/openapi/coupondroid-it-llms-txt-api-openapi.yml
- filename: coupondroid-it-mcp-api-openapi.yml
  format: yaml
  label: Coupondroid Italia MCP API
  slug: coupondroid-it-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-it/openapi/coupondroid-it-mcp-api-openapi.yml
- filename: coupondroid-it-well-known-api-openapi.yml
  format: yaml
  label: Coupondroid Italia .well Known API
  slug: coupondroid-it-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-it/openapi/coupondroid-it-well-known-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Il rapporto con gli utenti che accedono dall'Italia è regolato dalla legge italiana.
  entity_types:
  - text: Se sei un consumatore restano ferme le disposizioni inderogabili a tua tutela
    type: individual
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: È gratuito e non richiede registrazione.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Coupondroid Italia
provenance_date: '2026-11-09'
provider_name: Coupondroid Italia
provider_slug: coupondroid-it
slug: coupondroid-it-eligibility
source_date: '2026-11-09'
source_filename: coupondroid-it-eligibility.yml
source_heading: Eligibility
source_page: https://coupondroid.it/corp/termini-e-condizioni
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coupondroid Italia\naid: coupondroid-it\nurl: https://coupondroid.it/corp/termini-e-condizioni\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Il rapporto con gli utenti che accedono dall'Italia è regolato dalla legge italiana.\nentity_types:\n- type: individual\n  text: Se sei un consumatore restano ferme le disposizioni inderogabili a tua tutela\nrestricted_uses: []\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: È gratuito e non richiede registrazione.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/coupondroid-it/eligibility/coupondroid-it-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
summary_line: 3 quoted statements, read from Coupondroid Italia's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Coupons
- Discount Codes
- Deals
- E-Commerce
- Affiliate Marketing
- Italy
- MCP
---
