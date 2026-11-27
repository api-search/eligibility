---
api_specs:
- filename: posteahora-accounts-api-openapi.yml
  format: yaml
  label: PosteAhora Accounts API
  slug: posteahora-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/posteahora/openapi/posteahora-accounts-api-openapi.yml
- filename: posteahora-analytics-api-openapi.yml
  format: yaml
  label: PosteAhora Analytics API
  slug: posteahora-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/posteahora/openapi/posteahora-analytics-api-openapi.yml
- filename: posteahora-ideas-api-openapi.yml
  format: yaml
  label: PosteAhora Ideas API
  slug: posteahora-ideas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/posteahora/openapi/posteahora-ideas-api-openapi.yml
- filename: posteahora-media-api-openapi.yml
  format: yaml
  label: PosteAhora Media API
  slug: posteahora-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/posteahora/openapi/posteahora-media-api-openapi.yml
- filename: posteahora-posts-api-openapi.yml
  format: yaml
  label: PosteAhora Posts API
  slug: posteahora-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/posteahora/openapi/posteahora-posts-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Be at least 13 years old (or 16 in the EU) and have the legal capacity to enter into contracts
    value: 13 (16 in the EU)
  restricted_uses:
  - summary: Acceptable use restrictions
    text: Violate any applicable local, state, national, or international law or regulation
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
name: PosteAhora
provenance_date: '2026-11-10'
provider_name: PosteAhora
provider_slug: posteahora
slug: posteahora-eligibility
source_date: '2026-11-10'
source_filename: posteahora-eligibility.yml
source_heading: Eligibility
source_page: https://posteahora.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PosteAhora\naid: posteahora\nurl: https://posteahora.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Acceptable use restrictions\n  text: Violate any applicable local, state, national, or international law or regulation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: 13 (16 in the EU)\n  text: Be at least 13 years old (or 16 in the EU) and have the legal capacity to enter into contracts\n"
source_yaml_url: https://artifacts.apis.io/posteahora/eligibility/posteahora-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from PosteAhora's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Social Media
- AI Automation
- Marketing
- Software-as-a-Service
---
