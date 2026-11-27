---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 (in the U.S.) or 16 (all other countries but the U.S.) years old to use our Software.
    type: individual
  minimum_age:
    text: You must be at least 13 (in the U.S.) or 16 (all other countries but the U.S.) years old to use our Software.
    value: 13 (U.S.) / 16 (other countries)
  restricted_uses:
  - summary: Lawful use only
    text: You may use our Software only as permitted by applicable law, including export control laws and regulations.
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
name: Llmware
provenance_date: '2026-11-09'
provider_name: Llmware
provider_slug: llmware
slug: llmware-eligibility
source_date: '2026-11-09'
source_filename: llmware-eligibility.yml
source_heading: Eligibility
source_page: https://llmware.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Llmware\naid: llmware\nurl: https://llmware.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 (in the U.S.) or 16 (all other countries but the U.S.) years old to use our Software.\nrestricted_uses:\n- summary: Lawful use only\n  text: You may use our Software only as permitted by applicable law, including export control laws and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: 13 (U.S.) / 16 (other countries)\n  text: You\
  \ must be at least 13 (in the U.S.) or 16 (all other countries but the U.S.) years old to use our Software.\n"
source_yaml_url: https://artifacts.apis.io/llmware/eligibility/llmware-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Llmware's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Enterprise
- Workflows
- Private
- LLM
---
