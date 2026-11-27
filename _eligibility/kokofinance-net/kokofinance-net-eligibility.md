---
api_specs:
- filename: kokofinance-net-billing-api-openapi.yml
  format: yaml
  label: kokofinance-net Billing API
  slug: kokofinance-net-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kokofinance-net/openapi/kokofinance-net-billing-api-openapi.yml
- filename: kokofinance-net-cards-api-openapi.yml
  format: yaml
  label: kokofinance-net Cards API
  slug: kokofinance-net-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kokofinance-net/openapi/kokofinance-net-cards-api-openapi.yml
- filename: kokofinance-net-developers-api-openapi.yml
  format: yaml
  label: kokofinance-net Developers API
  slug: kokofinance-net-developers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kokofinance-net/openapi/kokofinance-net-developers-api-openapi.yml
- filename: kokofinance-net-intelligence-api-openapi.yml
  format: yaml
  label: kokofinance-net Intelligence API
  slug: kokofinance-net-intelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kokofinance-net/openapi/kokofinance-net-intelligence-api-openapi.yml
- filename: kokofinance-net-international-api-openapi.yml
  format: yaml
  label: kokofinance-net International API
  slug: kokofinance-net-international-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kokofinance-net/openapi/kokofinance-net-international-api-openapi.yml
- filename: kokofinance-net-platform-api-openapi.yml
  format: yaml
  label: kokofinance-net Platform API
  slug: kokofinance-net-platform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kokofinance-net/openapi/kokofinance-net-platform-api-openapi.yml
- filename: kokofinance-net-portfolio-api-openapi.yml
  format: yaml
  label: kokofinance-net Portfolio API
  slug: kokofinance-net-portfolio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kokofinance-net/openapi/kokofinance-net-portfolio-api-openapi.yml
- filename: kokofinance-net-reference-api-openapi.yml
  format: yaml
  label: kokofinance-net Reference API
  slug: kokofinance-net-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kokofinance-net/openapi/kokofinance-net-reference-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: '"You" refers to any individual, company, or entity accessing our services in any capacity.'
    type: individual
  - text: '"You" refers to any individual, company, or entity accessing our services in any capacity.'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful purposes only
    text: Use the service for lawful purposes only
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
name: kokofinance-net
provenance_date: '2026-11-09'
provider_name: kokofinance-net
provider_slug: kokofinance-net
slug: kokofinance-net-eligibility
source_date: '2026-11-09'
source_filename: kokofinance-net-eligibility.yml
source_heading: Eligibility
source_page: https://kokofinance.net/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: kokofinance-net\naid: kokofinance-net\nurl: https://kokofinance.net/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: '\"You\" refers to any individual, company, or entity accessing our services in any capacity.'\n- type: business\n  text: '\"You\" refers to any individual, company, or entity accessing our services in any capacity.'\nrestricted_uses:\n- summary: Lawful purposes only\n  text: Use the service for lawful purposes only\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kokofinance-net/eligibility/kokofinance-net-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from kokofinance-net's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Credit Cards
- MCP
---
