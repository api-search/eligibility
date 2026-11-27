---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: with no account and no sign-up.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Agent Reliability
provenance_date: '2026-11-09'
provider_name: Agent Reliability
provider_slug: agentreliability-dev
slug: agentreliability-dev-eligibility
source_date: '2026-11-09'
source_filename: agentreliability-dev-eligibility.yml
source_heading: Eligibility
source_page: https://agentreliability.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agent Reliability\naid: agentreliability-dev\nurl: https://agentreliability.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: with no account and no sign-up.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentreliability-dev/eligibility/agentreliability-dev-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from Agent Reliability's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Agents
- Reliability
- Benchmarking
- Testing
---
