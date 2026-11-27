---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE USING THE SERVICES ON BEHALF OF A COMPANY, ENTITY, OR ORGANIZATION
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No Prohibited Data or High Risk Activities
    text: Customer must not use a Service with Prohibited Data or for High Risk Activities.
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
name: Straiker
provenance_date: '2026-11-10'
provider_name: Straiker
provider_slug: straiker
slug: straiker-eligibility
source_date: '2026-11-10'
source_filename: straiker-eligibility.yml
source_heading: Eligibility
source_page: https://www.straiker.ai/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Straiker\naid: straiker\nurl: https://www.straiker.ai/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE USING THE SERVICES ON BEHALF OF A COMPANY, ENTITY, OR ORGANIZATION\nrestricted_uses:\n- summary: No Prohibited Data or High Risk Activities\n  text: Customer must not use a Service with Prohibited Data or for High Risk Activities.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/straiker/eligibility/straiker-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Straiker's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Artificial Intelligence
- AI Security
- AI Agents
- Runtime Security
- LLM Security
- MCP
---
