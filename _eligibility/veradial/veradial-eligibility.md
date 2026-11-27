---
api_specs:
- filename: veradial-hooks-api-openapi.yml
  format: yaml
  label: VeraDial Hooks API
  slug: veradial-hooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veradial/openapi/veradial-hooks-api-openapi.yml
- filename: veradial-keys-api-openapi.yml
  format: yaml
  label: VeraDial Keys API
  slug: veradial-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veradial/openapi/veradial-keys-api-openapi.yml
- filename: veradial-lines-api-openapi.yml
  format: yaml
  label: VeraDial Lines API
  slug: veradial-lines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veradial/openapi/veradial-lines-api-openapi.yml
- filename: veradial-me-api-openapi.yml
  format: yaml
  label: VeraDial Me API
  slug: veradial-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veradial/openapi/veradial-me-api-openapi.yml
- filename: veradial-samples-api-openapi.yml
  format: yaml
  label: VeraDial Samples API
  slug: veradial-samples-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veradial/openapi/veradial-samples-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: You must be at least 18 years of age and a resident of the United States or Canada to use VeraDial.
  entity_types:
  - text: VeraDial is for individual professionals and small businesses
    type: individual
  - text: VeraDial is for individual professionals and small businesses
    type: business
  minimum_age:
    text: You must be at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Restricted messaging content
    text: 'you may not use VeraDial messaging to send, promote, or facilitate content involving: Sexual, adult, or explicit content; hateful or harassing content'
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
name: VeraDial
provenance_date: '2026-11-10'
provider_name: VeraDial
provider_slug: veradial
slug: veradial-eligibility
source_date: '2026-11-10'
source_filename: veradial-eligibility.yml
source_heading: Eligibility
source_page: https://veradial.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: VeraDial\naid: veradial\nurl: https://veradial.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: You must be at least 18 years of age and a resident of the United States or Canada to use VeraDial.\nentity_types:\n- type: individual\n  text: VeraDial is for individual professionals and small businesses\n- type: business\n  text: VeraDial is for individual professionals and small businesses\nrestricted_uses:\n- summary: Restricted messaging content\n  text: 'you may not use VeraDial messaging to send, promote, or facilitate content involving: Sexual, adult, or\n\
  \    explicit content; hateful or harassing content'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/veradial/eligibility/veradial-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from VeraDial's own page on 2026-11-10.
synthetic: false
tags:
- AI Receptionist
- Business Phone
- Telephony
- Voice AI
- SMS
- Webhook
- MCP
- Small Business
---
