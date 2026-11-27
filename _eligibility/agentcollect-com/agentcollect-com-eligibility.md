---
api_specs:
- filename: agentcollect-com-openapi-generated.yml
  format: yaml
  label: AgentCollect API
  slug: agentcollect-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentcollect-com/openapi/_ae-authored/agentcollect-com-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: '"Customer," "you," or "your" means the business entity that registers for and uses the Platform.'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No consumer-debt collection
    text: You may not use the Platform to collect debts owed by individual consumers (as defined under the FDCPA and Regulation F)
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
name: AgentCollect
provenance_date: '2026-11-09'
provider_name: AgentCollect
provider_slug: agentcollect-com
slug: agentcollect-com-eligibility
source_date: '2026-11-09'
source_filename: agentcollect-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.agentcollect.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AgentCollect\naid: agentcollect-com\nurl: https://www.agentcollect.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: '\"Customer,\" \"you,\" or \"your\" means the business entity that registers for and uses the Platform.'\nrestricted_uses:\n- summary: No consumer-debt collection\n  text: You may not use the Platform to collect debts owed by individual consumers (as defined under the FDCPA and\n    Regulation F)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/agentcollect-com/eligibility/agentcollect-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from AgentCollect's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Artificial Intelligence
- Billing
- Payments
- Software-as-a-Service
- Company
---
