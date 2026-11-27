---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are 18 or older
    type: individual
  - text: If you are adopting or purchasing the Services on behalf of an Educational Institutional (such as your employer school) or other legal entity
    type: other
  minimum_age:
    text: You are 13–17 years old and your use of the Services (and our processing of your personal data) is legally permitted in your country.
    value: '13'
  restricted_uses:
  - summary: No commercial products or services
    text: such as using the Services to create or offer commercial products or services
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
name: Atypical AI
provenance_date: '2026-11-09'
provider_name: Atypical AI
provider_slug: atypical-ai
slug: atypical-ai-eligibility
source_date: '2026-11-09'
source_filename: atypical-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.atypicalai.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Atypical AI\naid: atypical-ai\nurl: https://www.atypicalai.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are 18 or older\n- type: other\n  text: If you are adopting or purchasing the Services on behalf of an Educational Institutional (such as your employer\n    school) or other legal entity\nrestricted_uses:\n- summary: No commercial products or services\n  text: such as using the Services to create or offer commercial products or services\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '13'\n  text: You are 13–17 years old and your use of the Services (and our processing of your personal data) is legally\n    permitted in your country.\n"
source_yaml_url: https://artifacts.apis.io/atypical-ai/eligibility/atypical-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Atypical AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Education
- EdTech
- Learning Science
- Generative AI
- Tutoring
- Exam Preparation
---
