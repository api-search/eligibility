---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this agreement on behalf of a company or legal entity, you represent that you have the authority to bind such entity.
    type: business
  minimum_age:
    text: The Service is intended solely for users who are eighteen (18) years of age or older.
    value: '18'
  restricted_uses:
  - summary: High-stakes automated decisions
    text: Using the Service to automate high-stakes decisions with significant legal or life-altering impacts (e.g., medical, credit, or legal determinations).
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
name: AgentLock
provenance_date: '2026-11-09'
provider_name: AgentLock
provider_slug: agentlock-net
slug: agentlock-net-eligibility
source_date: '2026-11-09'
source_filename: agentlock-net-eligibility.yml
source_heading: Eligibility
source_page: https://agentlock.net/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AgentLock\naid: agentlock-net\nurl: https://agentlock.net/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this agreement on behalf of a company or legal entity, you represent that you have\n    the authority to bind such entity.\nrestricted_uses:\n- summary: High-stakes automated decisions\n  text: Using the Service to automate high-stakes decisions with significant legal or life-altering impacts (e.g.,\n    medical, credit, or legal determinations).\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Service is intended solely for users who are eighteen (18) years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/agentlock-net/eligibility/agentlock-net-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AgentLock's own page on 2026-11-09.
synthetic: false
tags:
- AI Security
- Zero Trust
- API Gateway
- Agent Management
- Audit Trail
- Mobile approvals
---
