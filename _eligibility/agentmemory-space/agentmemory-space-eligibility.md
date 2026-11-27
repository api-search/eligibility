---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the service for an organization, you represent that you have authority to bind that organization.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sensitive or regulated data
    text: You must not submit secrets, regulated data, confidential third-party data, or personal information unless you have the legal right and appropriate safeguards to do so.
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
name: Agentmemory
provenance_date: '2026-11-09'
provider_name: Agentmemory
provider_slug: agentmemory-space
slug: agentmemory-space-eligibility
source_date: '2026-11-09'
source_filename: agentmemory-space-eligibility.yml
source_heading: Eligibility
source_page: https://agentmemory.space/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agentmemory\naid: agentmemory-space\nurl: https://agentmemory.space/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the service for an organization, you represent that you have authority to bind that organization.\nrestricted_uses:\n- summary: Sensitive or regulated data\n  text: You must not submit secrets, regulated data, confidential third-party data, or personal information unless\n    you have the legal right and appropriate safeguards to do so.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentmemory-space/eligibility/agentmemory-space-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Agentmemory's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Memory
- Platform
- Team
- Agents
---
