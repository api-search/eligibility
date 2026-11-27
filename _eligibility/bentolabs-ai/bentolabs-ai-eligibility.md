---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer may only use the Services in jurisdictions authorized by Bento Labs.
  entity_types:
  - text: Customer is validly existing and in good standing under the laws of the place of its establishment or incorporation
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Internal business use only
    text: The Services are provided to Customer only for Customer's internal business use and not for the benefit or use of any third party.
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
name: Bentolabs AI
provenance_date: '2026-11-09'
provider_name: Bentolabs AI
provider_slug: bentolabs-ai
slug: bentolabs-ai-eligibility
source_date: '2026-11-09'
source_filename: bentolabs-ai-eligibility.yml
source_heading: Eligibility
source_page: https://bentolabs.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bentolabs AI\naid: bentolabs-ai\nurl: https://bentolabs.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer may only use the Services in jurisdictions authorized by Bento Labs.\nentity_types:\n- type: business\n  text: Customer is validly existing and in good standing under the laws of the place of its establishment or incorporation\nrestricted_uses:\n- summary: Internal business use only\n  text: The Services are provided to Customer only for Customer's internal business use and not for the benefit\n    or use of any third party.\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bentolabs-ai/eligibility/bentolabs-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Bentolabs AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- Observability
- OpenTelemetry
- Tracing
- LLM Monitoring
- Evaluation
- Agent Infrastructure
- Developer Tools
---
