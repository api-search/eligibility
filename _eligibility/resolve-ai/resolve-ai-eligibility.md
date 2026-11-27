---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use our Site.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use our Site.
    value: '18'
  restricted_uses:
  - summary: Security violations
    text: You will not violate or attempt to violate the security of the Site or Resolve AI’s systems or network security
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
name: Resolve AI
provenance_date: '2026-11-10'
provider_name: Resolve AI
provider_slug: resolve-ai
slug: resolve-ai-eligibility
source_date: '2026-11-10'
source_filename: resolve-ai-eligibility.yml
source_heading: Eligibility
source_page: https://resolve.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Resolve AI\naid: resolve-ai\nurl: https://resolve.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use our Site.\nrestricted_uses:\n- summary: Security violations\n  text: You will not violate or attempt to violate the security of the Site or Resolve AI’s systems or network security\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use our Site.\n"
source_yaml_url: https://artifacts.apis.io/resolve-ai/eligibility/resolve-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Resolve AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Infrastructure
- Artificial Intelligence
- Site Reliability Engineering
- Observability
- Incident Response
- DevOps
- On-Call
- AI Agents
- MCP
- Incident Management
---
