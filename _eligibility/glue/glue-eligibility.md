---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is available only to individuals who are at least 18 years old.
    type: individual
  - text: IF YOU REPRESENT AN ENTITY (SUCH AS A COMPANY YOU ARE EMPLOYED BY), THIS AGREEMENT IS BINDING ON SUCH ENTITY
    type: business
  minimum_age:
    text: The Service is available only to individuals who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Unlawful or prohibited use
    text: You may not use the Service for any purpose that is unlawful or prohibited by this Agreement
  - summary: Competing product development
    text: You may not use the Service to develop any products or services that compete with our products and services.
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
name: Glue
provenance_date: '2026-11-09'
provider_name: Glue
provider_slug: glue
slug: glue-eligibility
source_date: '2026-11-09'
source_filename: glue-eligibility.yml
source_heading: Eligibility
source_page: https://glue.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Glue\naid: glue\nurl: https://glue.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Service is available only to individuals who are at least 18 years old.\n- type: business\n  text: IF YOU REPRESENT AN ENTITY (SUCH AS A COMPANY YOU ARE EMPLOYED BY), THIS AGREEMENT IS BINDING ON SUCH ENTITY\nrestricted_uses:\n- summary: Unlawful or prohibited use\n  text: You may not use the Service for any purpose that is unlawful or prohibited by this Agreement\n- summary: Competing product development\n  text: You may not use the Service\
  \ to develop any products or services that compete with our products and services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Service is available only to individuals who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/glue/eligibility/glue-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Glue's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Team Communication
- Messaging
- Collaboration
- GraphQL
- Webhook
- MCP
- Productivity
- AI Agents
---
