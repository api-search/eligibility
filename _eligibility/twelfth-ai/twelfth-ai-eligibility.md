---
api_specs:
- filename: twelfth-ai-tasks-api-openapi.yml
  format: yaml
  label: twelfth-ai Tasks API
  slug: twelfth-ai-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twelfth-ai/openapi/twelfth-ai-tasks-api-openapi.yml
- filename: twelfth-ai-workspace-api-openapi.yml
  format: yaml
  label: twelfth-ai Workspace API
  slug: twelfth-ai-workspace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twelfth-ai/openapi/twelfth-ai-workspace-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use the Website.
    type: individual
  - text: If you access or use the Website on behalf of a company, organisation or other entity, you represent and warrant that you have authority to do so and to bind that entity to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Website.
    value: '18'
  restricted_uses:
  - summary: Lawful use only
    text: You must use the Website only for lawful purposes and in accordance with these Terms.
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
name: twelfth-ai
provenance_date: '2026-11-10'
provider_name: twelfth-ai
provider_slug: twelfth-ai
slug: twelfth-ai-eligibility
source_date: '2026-11-10'
source_filename: twelfth-ai-eligibility.yml
source_heading: Eligibility
source_page: https://twelfth.ai/legals/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: twelfth-ai\naid: twelfth-ai\nurl: https://twelfth.ai/legals/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Website.\n- type: business\n  text: If you access or use the Website on behalf of a company, organisation or other entity, you represent and\n    warrant that you have authority to do so and to bind that entity to these Terms.\nrestricted_uses:\n- summary: Lawful use only\n  text: You must use the Website only for lawful purposes and in accordance with these Terms.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Website.\n"
source_yaml_url: https://artifacts.apis.io/twelfth-ai/eligibility/twelfth-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from twelfth-ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Retail
- Commerce
- Artificial Intelligence
- Workspace
---
