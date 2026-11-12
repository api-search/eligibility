---
api_specs:
- filename: coupondroid-com-a2a-api-openapi.yml
  format: yaml
  label: Coupondroid A2a API
  slug: coupondroid-com-a2a-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-com/openapi/coupondroid-com-a2a-api-openapi.yml
- filename: coupondroid-com-auth-md-api-openapi.yml
  format: yaml
  label: Coupondroid Auth.md API
  slug: coupondroid-com-auth-md-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-com/openapi/coupondroid-com-auth-md-api-openapi.yml
- filename: coupondroid-com-llms-txt-api-openapi.yml
  format: yaml
  label: Coupondroid Llms.txt API
  slug: coupondroid-com-llms-txt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-com/openapi/coupondroid-com-llms-txt-api-openapi.yml
- filename: coupondroid-com-mcp-api-openapi.yml
  format: yaml
  label: Coupondroid MCP API
  slug: coupondroid-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-com/openapi/coupondroid-com-mcp-api-openapi.yml
- filename: coupondroid-com-well-known-api-openapi.yml
  format: yaml
  label: Coupondroid .well Known API
  slug: coupondroid-com-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-com/openapi/coupondroid-com-well-known-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You should be at least 13 to use Coupondroid, which is written for adults.
    value: '13'
  restricted_uses:
  - summary: Personal non-commercial use only
    text: Use the site for your own personal, non-commercial shopping
  - summary: No illegal use or impersonation
    text: Use the site to break the law, infringe someone's rights, or pass yourself off as Coupondroid.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: No account is required and nothing here costs money.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Coupondroid
provenance_date: '2026-11-09'
provider_name: Coupondroid
provider_slug: coupondroid-com
slug: coupondroid-com-eligibility
source_date: '2026-11-09'
source_filename: coupondroid-com-eligibility.yml
source_heading: Eligibility
source_page: https://coupondroid.com/corp/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coupondroid\naid: coupondroid-com\nurl: https://coupondroid.com/corp/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Personal non-commercial use only\n  text: Use the site for your own personal, non-commercial shopping\n- summary: No illegal use or impersonation\n  text: Use the site to break the law, infringe someone's rights, or pass yourself off as Coupondroid.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: No account is required and nothing here costs money.\nminimum_age:\n  value:\
  \ '13'\n  text: You should be at least 13 to use Coupondroid, which is written for adults.\n"
source_yaml_url: https://artifacts.apis.io/coupondroid-com/eligibility/coupondroid-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Coupondroid's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Coupons
- Deals
- E-Commerce
- Shopping
- Affiliate Marketing
- MCP
- AI Agents
---
