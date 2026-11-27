---
api_specs:
- filename: creativeclaw-co-health-api-openapi.yml
  format: yaml
  label: CreativeClaw Health API
  slug: creativeclaw-co-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/creativeclaw-co/openapi/creativeclaw-co-health-api-openapi.yml
- filename: creativeclaw-co-mcp-api-openapi.yml
  format: yaml
  label: CreativeClaw MCP API
  slug: creativeclaw-co-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/creativeclaw-co/openapi/creativeclaw-co-mcp-api-openapi.yml
- filename: creativeclaw-co-oauth-api-openapi.yml
  format: yaml
  label: CreativeClaw OAuth API
  slug: creativeclaw-co-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/creativeclaw-co/openapi/creativeclaw-co-oauth-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not located in, or a resident of, any country subject to U.S. trade sanctions, and that you are not on any U.S. government restricted parties list.
  entity_types:
  - text: You must be at least 18 years old (or the age of legal majority in your jurisdiction) to use our Services.
    type: individual
  minimum_age:
    text: You must be at least 18 years old (or the age of legal majority in your jurisdiction) to use our Services.
    value: '18'
  restricted_uses:
  - summary: Voice cloning without speaker permission
    text: Do not clone a voice without the speaker's permission, impersonate someone deceptively, misrepresent an endorsement, or use generated speech to defraud or harm others.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must create an account to use the Services. You authenticate via Google (Gmail) OAuth.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CreativeClaw
provenance_date: '2026-11-09'
provider_name: CreativeClaw
provider_slug: creativeclaw-co
slug: creativeclaw-co-eligibility
source_date: '2026-11-09'
source_filename: creativeclaw-co-eligibility.yml
source_heading: Eligibility
source_page: https://creativeclaw.co/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CreativeClaw\naid: creativeclaw-co\nurl: https://creativeclaw.co/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not located in, or a resident of, any country subject to U.S. trade sanctions,\n    and that you are not on any U.S. government restricted parties list.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old (or the age of legal majority in your jurisdiction) to use our Services.\nrestricted_uses:\n- summary: Voice cloning without speaker permission\n  text: Do not clone a voice without the speaker's permission,\
  \ impersonate someone deceptively, misrepresent an\n    endorsement, or use generated speech to defraud or harm others.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must create an account to use the Services. You authenticate via Google (Gmail) OAuth.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of legal majority in your jurisdiction) to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/creativeclaw-co/eligibility/creativeclaw-co-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from CreativeClaw's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Generative AI
- Image Generation
- Video Generation
- Audio
- MCP
- Marketing
---
