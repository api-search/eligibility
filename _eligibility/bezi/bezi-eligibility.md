---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Services only if you are at least 13 years of age (or such other minimum age at which you can provide consent to data processing under the laws of your territory)
    type: individual
  - text: If you are using the Services on behalf of a company or other legal entity, you represent and warrant that you have the authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: You may use the Services only if you are at least 13 years of age (or such other minimum age at which you can provide consent to data processing under the laws of your territory)
    value: '13'
  restricted_uses:
  - summary: Prohibited content generation
    text: 'Post, upload, publish, submit or transmit any User Material, Input or Output or use the Services to create or distribute any User Material or Output, that: (i) infringes, misappropriates or violates a third party’s patent, copyright, trademark, trade secret, moral rights or other intellectual property rights'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may need to provide additional information to verify your identity before completing your Transaction (such information is included within the definition of Payment Information).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bezi
provenance_date: '2026-11-09'
provider_name: Bezi
provider_slug: bezi
slug: bezi-eligibility
source_date: '2026-11-09'
source_filename: bezi-eligibility.yml
source_heading: Eligibility
source_page: https://www.bezi.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bezi\naid: bezi\nurl: https://www.bezi.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Services only if you are at least 13 years of age (or such other minimum age at which you\n    can provide consent to data processing under the laws of your territory)\n- type: business\n  text: If you are using the Services on behalf of a company or other legal entity, you represent and warrant that\n    you have the authority to bind that entity to these Terms.\nrestricted_uses:\n- summary: Prohibited content\
  \ generation\n  text: 'Post, upload, publish, submit or transmit any User Material, Input or Output or use the Services to create\n    or distribute any User Material or Output, that: (i) infringes, misappropriates or violates a third party’s\n    patent, copyright, trademark, trade secret, moral rights or other intellectual property rights'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may need to provide additional information to verify your identity before completing your Transaction\n    (such information is included within the definition of Payment Information).\nminimum_age:\n  value: '13'\n  text: You may use the Services only if you are at least 13 years of age (or such other minimum age at which you\n    can provide consent to data processing under the laws of your territory)\n"
source_yaml_url: https://artifacts.apis.io/bezi/eligibility/bezi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Bezi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Game Development
- Unity
- Developer Tools
- AI Agents
- Coding Assistant
---
