---
api_specs:
- filename: cleve-ai-folders-api-openapi.yml
  format: yaml
  label: Cleve Folders API
  slug: cleve-ai-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cleve-ai/openapi/cleve-ai-folders-api-openapi.yml
- filename: cleve-ai-notes-api-openapi.yml
  format: yaml
  label: Cleve Notes API
  slug: cleve-ai-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cleve-ai/openapi/cleve-ai-notes-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use the Services.
    type: individual
  - text: If you use the Services on behalf of an organization, you represent that you have authority to bind that organization, and "you" includes the organization.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Services.
    value: '18'
  restricted_uses:
  - summary: Unlawful, harmful or abusive use
    text: Don't use it for illegal, harmful, or abusive purposes.
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
name: Cleve
provenance_date: '2026-11-09'
provider_name: Cleve
provider_slug: cleve-ai
slug: cleve-ai-eligibility
source_date: '2026-11-09'
source_filename: cleve-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.cleve.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cleve\naid: cleve-ai\nurl: https://www.cleve.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Services.\n- type: business\n  text: If you use the Services on behalf of an organization, you represent that you have authority to bind that\n    organization, and \"you\" includes the organization.\nrestricted_uses:\n- summary: Unlawful, harmful or abusive use\n  text: Don't use it for illegal, harmful, or abusive purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/cleve-ai/eligibility/cleve-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Cleve's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Writing
- Knowledge Management
- Note Taking
- Collaboration
- Model Context Protocol
- Productivity
---
