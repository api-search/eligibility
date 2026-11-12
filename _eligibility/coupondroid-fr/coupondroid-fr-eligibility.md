---
api_specs:
- filename: coupondroid-fr-a2a-api-openapi.yml
  format: yaml
  label: Coupondroid France A2a API
  slug: coupondroid-fr-a2a-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-fr/openapi/coupondroid-fr-a2a-api-openapi.yml
- filename: coupondroid-fr-auth-md-api-openapi.yml
  format: yaml
  label: Coupondroid France Auth.md API
  slug: coupondroid-fr-auth-md-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-fr/openapi/coupondroid-fr-auth-md-api-openapi.yml
- filename: coupondroid-fr-llms-txt-api-openapi.yml
  format: yaml
  label: Coupondroid France Llms.txt API
  slug: coupondroid-fr-llms-txt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-fr/openapi/coupondroid-fr-llms-txt-api-openapi.yml
- filename: coupondroid-fr-mcp-api-openapi.yml
  format: yaml
  label: Coupondroid France MCP API
  slug: coupondroid-fr-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-fr/openapi/coupondroid-fr-mcp-api-openapi.yml
- filename: coupondroid-fr-well-known-api-openapi.yml
  format: yaml
  label: Coupondroid France .well Known API
  slug: coupondroid-fr-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-fr/openapi/coupondroid-fr-well-known-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: boutiques en ligne accessibles depuis la France
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: Le service est gratuit et ne nécessite aucune inscription
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Coupondroid France
provenance_date: '2026-11-09'
provider_name: Coupondroid France
provider_slug: coupondroid-fr
slug: coupondroid-fr-eligibility
source_date: '2026-11-09'
source_filename: coupondroid-fr-eligibility.yml
source_heading: Eligibility
source_page: https://coupondroid.fr/corp/conditions-generales
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coupondroid France\naid: coupondroid-fr\nurl: https://coupondroid.fr/corp/conditions-generales\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: boutiques en ligne accessibles depuis la France\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: Le service est gratuit et ne nécessite aucune inscription\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/coupondroid-fr/eligibility/coupondroid-fr-eligibility.yml
stated_fields:
- countries
- verification
summary_line: 2 quoted statements, read from Coupondroid France's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Coupons
- Promo Codes
- Deals
- E-Commerce
- Affiliate Marketing
- France
- MCP
---
