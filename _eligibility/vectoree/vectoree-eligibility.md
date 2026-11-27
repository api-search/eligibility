---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service on behalf of an organization, you represent that you have authority to bind that organization.
    type: business
  minimum_age:
    text: You must be able to form a binding contract and meet any age or export eligibility requirements.
    value: null
  restricted_uses:
  - summary: Acceptable use restrictions
    text: You may not use the Service to violate law, infringe others’ rights, distribute malware, probe or disrupt systems you do not own, bypass rate limits or security, mine cryptocurrency without authorization, or generate illegal or abusive content.
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
name: Vectoree
provenance_date: '2026-11-10'
provider_name: Vectoree
provider_slug: vectoree
slug: vectoree-eligibility
source_date: '2026-11-10'
source_filename: vectoree-eligibility.yml
source_heading: Eligibility
source_page: https://vectoree.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vectoree\naid: vectoree\nurl: https://vectoree.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service on behalf of an organization, you represent that you have authority to bind that\n    organization.\nrestricted_uses:\n- summary: Acceptable use restrictions\n  text: You may not use the Service to violate law, infringe others’ rights, distribute malware, probe or disrupt\n    systems you do not own, bypass rate limits or security, mine cryptocurrency without authorization, or generate\n    illegal or abusive\
  \ content.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You must be able to form a binding contract and meet any age or export eligibility requirements.\n"
source_yaml_url: https://artifacts.apis.io/vectoree/eligibility/vectoree-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Vectoree's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Backend-as-a-Service
- OpenAI-Compatible
- Agents
---
