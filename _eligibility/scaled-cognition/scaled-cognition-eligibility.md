---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer will not permit any User to access or use any Service or Content in a U.S.-embargoed country or region or in violation of any U.S. export law or regulation.
  entity_types:
  - text: In the case of an individual accepting these terms on his or her own behalf
    type: individual
  - text: IF THE INDIVIDUAL ACCEPTING THIS AGREEMENT IS ACCEPTING ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No high-risk medical or legal decisions
    text: You agree that the Output should not be used for any high risk decisions or implications, such as to make or provide medical or legal recommendations, decisions or determinations.
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
name: Scaled Cognition
provenance_date: '2026-11-10'
provider_name: Scaled Cognition
provider_slug: scaled-cognition
slug: scaled-cognition-eligibility
source_date: '2026-11-10'
source_filename: scaled-cognition-eligibility.yml
source_heading: Eligibility
source_page: https://www.scaledcognition.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Scaled Cognition\naid: scaled-cognition\nurl: https://www.scaledcognition.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Customer will not permit any User to access or use any Service or Content in a U.S.-embargoed country or\n    region or in violation of any U.S. export law or regulation.\nentity_types:\n- type: individual\n  text: In the case of an individual accepting these terms on his or her own behalf\n- type: business\n  text: IF THE INDIVIDUAL ACCEPTING THIS AGREEMENT IS ACCEPTING ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY\n\
  restricted_uses:\n- summary: No high-risk medical or legal decisions\n  text: You agree that the Output should not be used for any high risk decisions or implications, such as to make\n    or provide medical or legal recommendations, decisions or determinations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/scaled-cognition/eligibility/scaled-cognition-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Scaled Cognition's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Agents
- LLM
- Customer Experience
- Contact Center
- Conversational AI
- Voice
- Enterprise Software
- Machine Learning
- Company
---
