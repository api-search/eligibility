---
api_specs:
- filename: awraiter-ai-catalog-api-openapi.yml
  format: yaml
  label: AwrAiter Catalog API
  slug: awraiter-ai-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awraiter-ai/openapi/awraiter-ai-catalog-api-openapi.yml
- filename: awraiter-ai-read-api-openapi.yml
  format: yaml
  label: AwrAiter Read API
  slug: awraiter-ai-read-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awraiter-ai/openapi/awraiter-ai-read-api-openapi.yml
- filename: awraiter-ai-write-api-openapi.yml
  format: yaml
  label: AwrAiter Write API
  slug: awraiter-ai-write-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awraiter-ai/openapi/awraiter-ai-write-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and, if you act for a company, authorised to bind it.
    type: individual
  - text: if you act for a company, authorised to bind it.
    type: business
  minimum_age:
    text: You must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Processing others' personal data
    text: process other people's personal data through the Service without a lawful basis
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You sign in with your Telegram account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AwrAiter
provenance_date: '2026-11-09'
provider_name: AwrAiter
provider_slug: awraiter-ai
slug: awraiter-ai-eligibility
source_date: '2026-11-09'
source_filename: awraiter-ai-eligibility.yml
source_heading: Eligibility
source_page: https://awraiter.ai/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AwrAiter\naid: awraiter-ai\nurl: https://awraiter.ai/legal/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and, if you act for a company, authorised to bind it.\n- type: business\n  text: if you act for a company, authorised to bind it.\nrestricted_uses:\n- summary: Processing others' personal data\n  text: process other people's personal data through the Service without a lawful basis\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You sign in with your Telegram\
  \ account.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/awraiter-ai/eligibility/awraiter-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from AwrAiter's own page on 2026-11-09.
synthetic: false
tags:
- Telegram
- Content Planning
- Analytics
- AI Integration
- Software-as-a-Service
---
