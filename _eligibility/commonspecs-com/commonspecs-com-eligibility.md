---
api_specs:
- filename: commonspecs-com-openapi-generated.yml
  format: yaml
  label: commonspecs API
  slug: commonspecs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commonspecs-com/openapi/_ae-authored/commonspecs-com-openapi-generated.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is intended for businesses and professionals and is not directed to children under 16.
    type: business
  - text: If you are a consumer, your statutory withdrawal right applies
    type: individual
  minimum_age:
    text: The Service is intended for businesses and professionals and is not directed to children under 16.
    value: null
  restricted_uses:
  - summary: Illegal or unlawful use
    text: use the Service for any illegal purpose
  - summary: Unlawful content
    text: submit unlawful content
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You need an account with a verified email address.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: commonspecs
provenance_date: '2026-11-09'
provider_name: commonspecs
provider_slug: commonspecs-com
slug: commonspecs-com-eligibility
source_date: '2026-11-09'
source_filename: commonspecs-com-eligibility.yml
source_heading: Eligibility
source_page: https://commonspecs.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: commonspecs\naid: commonspecs-com\nurl: https://commonspecs.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is intended for businesses and professionals and is not directed to children under 16.\n- type: individual\n  text: If you are a consumer, your statutory withdrawal right applies\nrestricted_uses:\n- summary: Illegal or unlawful use\n  text: use the Service for any illegal purpose\n- summary: Unlawful content\n  text: submit unlawful content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: You need an account with a verified email address.\nminimum_age:\n  value: null\n  text: The Service is intended for businesses and professionals and is not directed to children under 16.\n"
source_yaml_url: https://artifacts.apis.io/commonspecs-com/eligibility/commonspecs-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from commonspecs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Product Data
- Product Specifications
- Price Comparison
- AI Agents
- MCP
- Agent Skills
- E-Commerce
---
