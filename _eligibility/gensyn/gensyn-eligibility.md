---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are at least eighteen (18) years old and are able to form a legally binding contract
    type: individual
  - text: if you access or use the Services on behalf of an entity, you have authority to bind that entity
    type: business
  minimum_age:
    text: you are at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Illegal activity
    text: You may not access or use the Services to conduct, promote, or facilitate illegal activity.
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
name: Gensyn
provenance_date: '2026-11-09'
provider_name: Gensyn
provider_slug: gensyn
slug: gensyn-eligibility
source_date: '2026-11-09'
source_filename: gensyn-eligibility.yml
source_heading: Eligibility
source_page: https://www.gensyn.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gensyn\naid: gensyn\nurl: https://www.gensyn.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you are at least eighteen (18) years old and are able to form a legally binding contract\n- type: business\n  text: if you access or use the Services on behalf of an entity, you have authority to bind that entity\nrestricted_uses:\n- summary: Illegal activity\n  text: You may not access or use the Services to conduct, promote, or facilitate illegal activity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/gensyn/eligibility/gensyn-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Gensyn's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Decentralized Compute
- Blockchain
- Prediction Markets
- Agents
- Web3
---
