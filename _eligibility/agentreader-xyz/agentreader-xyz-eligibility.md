---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use it for an organisation, you confirm you may accept them on its behalf.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Acceptable use restrictions
    text: 'Don''t use the Service to: fetch, store or spread illegal content, or for any illegal purpose'
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
name: AgentReader
provenance_date: '2026-11-09'
provider_name: AgentReader
provider_slug: agentreader-xyz
slug: agentreader-xyz-eligibility
source_date: '2026-11-09'
source_filename: agentreader-xyz-eligibility.yml
source_heading: Eligibility
source_page: https://agentreader.xyz/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AgentReader\naid: agentreader-xyz\nurl: https://agentreader.xyz/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use it for an organisation, you confirm you may accept them on its behalf.\nrestricted_uses:\n- summary: Acceptable use restrictions\n  text: 'Don''t use the Service to: fetch, store or spread illegal content, or for any illegal purpose'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentreader-xyz/eligibility/agentreader-xyz-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from AgentReader's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Data Processing
- PDF
- Markdown
- Agent Tools
---
