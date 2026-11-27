---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be a human. Accounts registered by “bots” or other automated methods are not permitted.
    type: individual
  - text: When we say “You” or “your”, we are referring to the people or organizations that own an account with one or more of our Services.
    type: business
  minimum_age:
    text: You need to be 18 or older.
    value: '18'
  restricted_uses:
  - summary: Prohibited jurisdictions
    text: Do not use the Services in regions or countries where the use of the Services is prohibited by law or where Gimlet Labs has decided not to provide services.
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
name: Gimlet Labs
provenance_date: '2026-11-09'
provider_name: Gimlet Labs
provider_slug: gimlet-labs
slug: gimlet-labs-eligibility
source_date: '2026-11-09'
source_filename: gimlet-labs-eligibility.yml
source_heading: Eligibility
source_page: https://gimletlabs.ai/legal/terms_and_conditions/terms_of_service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gimlet Labs\naid: gimlet-labs\nurl: https://gimletlabs.ai/legal/terms_and_conditions/terms_of_service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be a human. Accounts registered by “bots” or other automated methods are not permitted.\n- type: business\n  text: When we say “You” or “your”, we are referring to the people or organizations that own an account with one\n    or more of our Services.\nrestricted_uses:\n- summary: Prohibited jurisdictions\n  text: Do not use the Services in regions or countries where the use of\
  \ the Services is prohibited by law or where\n    Gimlet Labs has decided not to provide services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You need to be 18 or older.\n"
source_yaml_url: https://artifacts.apis.io/gimlet-labs/eligibility/gimlet-labs-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Gimlet Labs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Infrastructure
- Machine Learning
- Inference
- Agents
- Compilers
- GPU
- Serverless
---
