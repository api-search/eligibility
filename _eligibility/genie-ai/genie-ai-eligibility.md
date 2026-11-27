---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The individual or entity who is accessing, downloading, or using our Software and Services
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No domestic or personal use
    text: the Software will not be used for any domestic, personal, or non-commercial use
  - summary: No automated decision-making with legal effects
    text: You will not (and will ensure that no Authorised User will) use the Software for any automated decision-making that has legal or similarly significant effects on, or other important decisions about, individuals.
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
name: Genie AI
provenance_date: '2026-11-09'
provider_name: Genie AI
provider_slug: genie-ai
slug: genie-ai-eligibility
source_date: '2026-11-09'
source_filename: genie-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.genieai.co/product-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Genie AI\naid: genie-ai\nurl: https://www.genieai.co/product-terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The individual or entity who is accessing, downloading, or using our Software and Services\nrestricted_uses:\n- summary: No domestic or personal use\n  text: the Software will not be used for any domestic, personal, or non-commercial use\n- summary: No automated decision-making with legal effects\n  text: You will not (and will ensure that no Authorised User will) use the Software for any automated\
  \ decision-making\n    that has legal or similarly significant effects on, or other important decisions about, individuals.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/genie-ai/eligibility/genie-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Genie AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Legal
- Legal Tech
- Contracts
- Contract Management
- Legal AI
- Document Automation
- Compliance
- Agents
---
