---
api_specs:
- filename: weirapp-io-account-api-openapi.yml
  format: yaml
  label: weirapp-io Account API
  slug: weirapp-io-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weirapp-io/openapi/weirapp-io-account-api-openapi.yml
- filename: weirapp-io-monitors-api-openapi.yml
  format: yaml
  label: weirapp-io Monitors API
  slug: weirapp-io-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weirapp-io/openapi/weirapp-io-monitors-api-openapi.yml
- filename: weirapp-io-reddit-api-openapi.yml
  format: yaml
  label: weirapp-io Reddit API
  slug: weirapp-io-reddit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weirapp-io/openapi/weirapp-io-reddit-api-openapi.yml
- filename: weirapp-io-system-api-openapi.yml
  format: yaml
  label: weirapp-io System API
  slug: weirapp-io-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weirapp-io/openapi/weirapp-io-system-api-openapi.yml
- filename: weirapp-io-webhooks-api-openapi.yml
  format: yaml
  label: weirapp-io Webhooks API
  slug: weirapp-io-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weirapp-io/openapi/weirapp-io-webhooks-api-openapi.yml
- filename: weirapp-io-x-api-openapi.yml
  format: yaml
  label: weirapp-io X API
  slug: weirapp-io-x-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weirapp-io/openapi/weirapp-io-x-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old, or the age of majority where you live if that is higher, to use the Service.
    type: individual
  - text: If you use the Service on behalf of a company or other organisation, you confirm that you are authorised to accept these Terms for it, and “you” includes that organisation.
    type: business
  minimum_age:
    text: You must be at least 18 years old, or the age of majority where you live if that is higher, to use the Service.
    value: '18'
  restricted_uses:
  - summary: Harassment, surveillance, spam
    text: Do not use Weir to harass, surveil, or spam people, or to break the law.
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
name: weirapp-io
provenance_date: '2026-11-10'
provider_name: weirapp-io
provider_slug: weirapp-io
slug: weirapp-io-eligibility
source_date: '2026-11-10'
source_filename: weirapp-io-eligibility.yml
source_heading: Eligibility
source_page: https://weirapp.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: weirapp-io\naid: weirapp-io\nurl: https://weirapp.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old, or the age of majority where you live if that is higher, to use the Service.\n- type: business\n  text: If you use the Service on behalf of a company or other organisation, you confirm that you are authorised\n    to accept these Terms for it, and “you” includes that organisation.\nrestricted_uses:\n- summary: Harassment, surveillance, spam\n  text: Do not use Weir to harass, surveil, or spam\
  \ people, or to break the law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age of majority where you live if that is higher, to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/weirapp-io/eligibility/weirapp-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from weirapp-io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data
- Social Media
- MCP
---
