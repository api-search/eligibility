---
api_specs:
- filename: everypage-co-account-api-openapi.yml
  format: yaml
  label: EveryPage Account API
  slug: everypage-co-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everypage-co/openapi/everypage-co-account-api-openapi.yml
- filename: everypage-co-embedding-api-openapi.yml
  format: yaml
  label: EveryPage Embedding API
  slug: everypage-co-embedding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everypage-co/openapi/everypage-co-embedding-api-openapi.yml
- filename: everypage-co-events-api-openapi.yml
  format: yaml
  label: EveryPage Events API
  slug: everypage-co-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everypage-co/openapi/everypage-co-events-api-openapi.yml
- filename: everypage-co-files-api-openapi.yml
  format: yaml
  label: EveryPage Files API
  slug: everypage-co-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everypage-co/openapi/everypage-co-files-api-openapi.yml
- filename: everypage-co-oauth-api-openapi.yml
  format: yaml
  label: EveryPage OAuth API
  slug: everypage-co-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everypage-co/openapi/everypage-co-oauth-api-openapi.yml
- filename: everypage-co-variants-api-openapi.yml
  format: yaml
  label: EveryPage Variants API
  slug: everypage-co-variants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everypage-co/openapi/everypage-co-variants-api-openapi.yml
- filename: everypage-co-webhooks-api-openapi.yml
  format: yaml
  label: EveryPage Webhooks API
  slug: everypage-co-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everypage-co/openapi/everypage-co-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'An account belongs to one person: do not share your login.'
    type: individual
  - text: If you use EveryPage for business, you agree to cover our reasonable losses, costs and legal fees
    type: business
  minimum_age:
    text: You must be at least 16 years old to hold an account.
    value: '16'
  restricted_uses:
  - summary: Prohibited content
    text: Content that promotes terrorism or violent extremism.
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
name: EveryPage
provenance_date: '2026-11-09'
provider_name: EveryPage
provider_slug: everypage-co
slug: everypage-co-eligibility
source_date: '2026-11-09'
source_filename: everypage-co-eligibility.yml
source_heading: Eligibility
source_page: https://everypage.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EveryPage\naid: everypage-co\nurl: https://everypage.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'An account belongs to one person: do not share your login.'\n- type: business\n  text: If you use EveryPage for business, you agree to cover our reasonable losses, costs and legal fees\nrestricted_uses:\n- summary: Prohibited content\n  text: Content that promotes terrorism or violent extremism.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must\
  \ be at least 16 years old to hold an account.\n"
source_yaml_url: https://artifacts.apis.io/everypage-co/eligibility/everypage-co-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from EveryPage's own page on 2026-11-09.
synthetic: false
tags:
- PDF
- Document Sharing
- ReaderAnalytics
- Privacy
- Software-as-a-Service
---
