---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this Agreement on behalf of a company, business or other legal entity, you represent that you have the authority to bind such entity to this Agreement
    type: business
  minimum_age:
    text: Our Platform is not intended for minors under the age of 18.
    value: '18'
  restricted_uses:
  - summary: Free tier non-commercial only
    text: RadixArk may make available a free tier of the Platform for non-commercial purposes only.
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
name: RadixArk
provenance_date: '2026-11-10'
provider_name: RadixArk
provider_slug: radixark
slug: radixark-eligibility
source_date: '2026-11-10'
source_filename: radixark-eligibility.yml
source_heading: Eligibility
source_page: https://www.radixark.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RadixArk\naid: radixark\nurl: https://www.radixark.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this Agreement on behalf of a company, business or other legal entity, you represent\n    that you have the authority to bind such entity to this Agreement\nrestricted_uses:\n- summary: Free tier non-commercial only\n  text: RadixArk may make available a free tier of the Platform for non-commercial purposes only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: Our Platform is not intended for minors under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/radixark/eligibility/radixark-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from RadixArk's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Infrastructure
- Machine Learning
- LLM
- Inference
- Reinforcement Learning
- Open Source
---
