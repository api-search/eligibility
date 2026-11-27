---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not located, organized or resident in a country that is or becomes subject to comprehensive Trade Controls or prohibited from receiving Services under applicable Trade Controls
  entity_types:
  - text: If you are an enterprise customer that enters into an Enterprise Agreement with Company for use of the Services hereunder
    type: business
  - text: For any individual who procures a right to use the Services on behalf of an entity or organization, such entity or organization is considered the Customer hereunder
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No submission of children's or sensitive data
    text: Submit or upload to the Services any information or data that is subject to safeguarding and/or limitations on distribution pursuant to applicable laws and/or regulations, including information that you know or reasonably should know is from or about children under the age of 13
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
name: Thinking Machines
provenance_date: '2026-11-10'
provider_name: Thinking Machines
provider_slug: thinking-machines
slug: thinking-machines-eligibility
source_date: '2026-11-10'
source_filename: thinking-machines-eligibility.yml
source_heading: Eligibility
source_page: https://thinkingmachines.ai/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Thinking Machines\naid: thinking-machines\nurl: https://thinkingmachines.ai/legal/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are not located, organized or resident in a country that is or becomes subject to comprehensive Trade\n    Controls or prohibited from receiving Services under applicable Trade Controls\nentity_types:\n- type: business\n  text: If you are an enterprise customer that enters into an Enterprise Agreement with Company for use of the Services\n    hereunder\n- type: individual\n  text: For any individual who procures a right to use the Services on\
  \ behalf of an entity or organization, such\n    entity or organization is considered the Customer hereunder\nrestricted_uses:\n- summary: No submission of children's or sensitive data\n  text: Submit or upload to the Services any information or data that is subject to safeguarding and/or limitations\n    on distribution pursuant to applicable laws and/or regulations, including information that you know or reasonably\n    should know is from or about children under the age of 13\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/thinking-machines/eligibility/thinking-machines-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Thinking Machines's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Fine-Tuning
- LLM
- Model Training
- Developer Tools
- Foundation Models
- Reinforcement Learning
---
