---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the service on behalf of an organization, you must have authority to accept these terms for it.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful, spam, fraud, malware, harassment uses
    text: Do not use the service for unlawful activity, spam, fraud, malware, harassment, or infringement of others' rights.
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
name: AgentAddress
provenance_date: '2026-11-09'
provider_name: AgentAddress
provider_slug: agentaddress-dev
slug: agentaddress-dev-eligibility
source_date: '2026-11-09'
source_filename: agentaddress-dev-eligibility.yml
source_heading: Eligibility
source_page: https://agentaddress.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AgentAddress\naid: agentaddress-dev\nurl: https://agentaddress.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the service on behalf of an organization, you must have authority to accept these terms for it.\nrestricted_uses:\n- summary: Unlawful, spam, fraud, malware, harassment uses\n  text: Do not use the service for unlawful activity, spam, fraud, malware, harassment, or infringement of others'\n    rights.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentaddress-dev/eligibility/agentaddress-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from AgentAddress's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Webhook
- Email
- Agents
---
