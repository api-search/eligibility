---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer may only use the Services in jurisdictions authorized by Judgment Labs. Customer represents that neither Customer nor Customer Personnel is located in, or a resident or national of, any country subject to a U.S. government embargo or other restriction.
  minimum_age:
    text: null
    value: null
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
name: Judgment Labs
provenance_date: '2026-11-09'
provider_name: Judgment Labs
provider_slug: judgment-labs
slug: judgment-labs-eligibility
source_date: '2026-11-09'
source_filename: judgment-labs-eligibility.yml
source_heading: Eligibility
source_page: https://app.judgmentlabs.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Judgment Labs\naid: judgment-labs\nurl: https://app.judgmentlabs.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer may only use the Services in jurisdictions authorized by Judgment Labs. Customer represents that\n    neither Customer nor Customer Personnel is located in, or a resident or national of, any country subject to\n    a U.S. government embargo or other restriction.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/judgment-labs/eligibility/judgment-labs-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Judgment Labs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Agents
- Artificial Intelligence
- Agent Evaluation
- Observability
- Tracing
- Monitoring
- LLM
- Developer Tools
- MCP
---
