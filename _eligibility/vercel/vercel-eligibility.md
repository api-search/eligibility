---
api_specs:
- filename: vercel-webhooks-asyncapi.yml
  format: yaml
  label: Vercel Webhooks
  slug: vercel-webhooks
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/vercel/asyncapi/vercel-webhooks-asyncapi.yml
- filename: vercel-chats-api-openapi.yml
  format: yaml
  label: Vercel Chats API
  slug: vercel-chats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vercel/openapi/vercel-chats-api-openapi.yml
- filename: vercel-embeddings-api-openapi.yml
  format: yaml
  label: Vercel Embeddings API
  slug: vercel-embeddings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vercel/openapi/vercel-embeddings-api-openapi.yml
- filename: vercel-models-api-openapi.yml
  format: yaml
  label: Vercel Models API
  slug: vercel-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vercel/openapi/vercel-models-api-openapi.yml
- filename: vercel-chat-completions-api-openapi.yml
  format: yaml
  label: Vercel Chat Completions API
  slug: vercel-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vercel/openapi/vercel-chat-completions-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You certify that you are a person at least 16 years of age.
    type: individual
  - text: If you are entering into this Agreement on behalf of a company, business or other legal entity, you represent that you have the authority to bind such an entity to this Agreement
    type: business
  minimum_age:
    text: You certify that you are a person at least 16 years of age.
    value: '16'
  restricted_uses:
  - summary: Hobby plan non-commercial only
    text: You shall only use the Services under a Hobby plan for your personal or non-commercial use.
  - summary: Sanctioned persons excluded
    text: you are not the target of sanctions administered or enforced by the U.S. Department of the Treasury's Office of Foreign Assets Control
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
name: Vercel
provenance_date: '2026-11-10'
provider_name: Vercel
provider_slug: vercel
slug: vercel-eligibility
source_date: '2026-11-10'
source_filename: vercel-eligibility.yml
source_heading: Eligibility
source_page: https://vercel.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vercel\naid: vercel\nurl: https://vercel.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You certify that you are a person at least 16 years of age.\n- type: business\n  text: If you are entering into this Agreement on behalf of a company, business or other legal entity, you represent\n    that you have the authority to bind such an entity to this Agreement\nrestricted_uses:\n- summary: Hobby plan non-commercial only\n  text: You shall only use the Services under a Hobby plan for your personal or non-commercial use.\n\
  - summary: Sanctioned persons excluded\n  text: you are not the target of sanctions administered or enforced by the U.S. Department of the Treasury's Office\n    of Foreign Assets Control\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You certify that you are a person at least 16 years of age.\n"
source_yaml_url: https://artifacts.apis.io/vercel/eligibility/vercel-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Vercel's own page on 2026-11-10.
synthetic: false
tags:
- AI Gateway
- Gateways
- Observability
- Webhook
- Serverless
- Hosting
- Deployment
---
