---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'If you are accepting on behalf of your employer or another entity, you represent and warrant that: (i) you have full legal authority to bind your employer or such entity to these Terms'
    type: business
  - text: Any United States federal, state, or local government customers are subject to a separate agreement.
    type: government
  minimum_age:
    text: The Cloud Products are not intended for, and should not be used by, anyone under the age of 16.
    value: '16'
  restricted_uses:
  - summary: No prohibited end uses
    text: You agree not to use or provide the Cloud Products for any prohibited end use, including to support any nuclear, chemical, or biological weapons proliferation, or missile technology
  - summary: No sensitive personal information unless supported
    text: You will not submit to the Cloud Products (or use the Cloud Products to collect) any Sensitive Personal Information unless its processing is expressly supported as a feature of the applicable Cloud Product
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
name: VISO
provenance_date: '2026-11-10'
provider_name: VISO
provider_slug: viso
slug: viso-eligibility
source_date: '2026-11-10'
source_filename: viso-eligibility.yml
source_heading: Eligibility
source_page: https://viso.ai/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: VISO\naid: viso\nurl: https://viso.ai/legal/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'If you are accepting on behalf of your employer or another entity, you represent and warrant that: (i)\n    you have full legal authority to bind your employer or such entity to these Terms'\n- type: government\n  text: Any United States federal, state, or local government customers are subject to a separate agreement.\nrestricted_uses:\n- summary: No prohibited end uses\n  text: You agree not to use or provide\
  \ the Cloud Products for any prohibited end use, including to support any\n    nuclear, chemical, or biological weapons proliferation, or missile technology\n- summary: No sensitive personal information unless supported\n  text: You will not submit to the Cloud Products (or use the Cloud Products to collect) any Sensitive Personal\n    Information unless its processing is expressly supported as a feature of the applicable Cloud Product\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: The Cloud Products are not intended for, and should not be used by, anyone under the age of 16.\n"
source_yaml_url: https://artifacts.apis.io/viso/eligibility/viso-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from VISO's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Computer Vision
- Machine Learning
- Video Analytics
- Vision Agents
- Edge AI
- GraphQL
- No-Code
---
