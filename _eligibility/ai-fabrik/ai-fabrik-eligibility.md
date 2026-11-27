---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you are not located in, under the control of, or a resident of any country subject to U.S. embargo, and are not listed on any U.S. government restricted party list.
  entity_types:
  - text: If you are using the Services on behalf of an organization, you represent that you have authority to bind that organization.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Services.
    value: '18'
  restricted_uses:
  - summary: Sensitive personal data submission
    text: 'You agree not to submit sensitive personal data, including:'
  - summary: Unlawful use
    text: Use the Services for unlawful purposes
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
name: Ai Fabrik
provenance_date: '2026-11-09'
provider_name: Ai Fabrik
provider_slug: ai-fabrik
slug: ai-fabrik-eligibility
source_date: '2026-11-09'
source_filename: ai-fabrik-eligibility.yml
source_heading: Eligibility
source_page: https://aifabrik.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ai Fabrik\naid: ai-fabrik\nurl: https://aifabrik.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you are not located in, under the control of, or a resident of any country\n    subject to U.S. embargo, and are not listed on any U.S. government restricted party list.\nentity_types:\n- type: business\n  text: If you are using the Services on behalf of an organization, you represent that you have authority to bind\n    that organization.\nrestricted_uses:\n- summary: Sensitive personal data submission\n  text: 'You agree not to submit\
  \ sensitive personal data, including:'\n- summary: Unlawful use\n  text: Use the Services for unlawful purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/ai-fabrik/eligibility/ai-fabrik-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Ai Fabrik's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Inference
- Infrastructure
- Edge Computing
- GPU
- Data Center
- Real-Time AI
---
