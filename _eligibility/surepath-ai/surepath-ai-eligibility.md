---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: SurePath’s software-as-a-service platform designed to enable businesses to control access to, and enforce corporate policy compliance applicable to, the business’s internal generative artificial intelligence (large language model) use
    type: business
  - text: any individual or entity that accesses and uses the Subscription Services
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export and sanctions compliance
    text: Customer affirms that it is not named on, owned by, or acting on behalf of any U.S. government denied-party list
  - summary: Prohibited weapons and missile applications
    text: used for any purposes prohibited by the Export Laws, including, but not limited to, nuclear, chemical, or biological weapons proliferation, missile systems or technology, or restricted unmanned aerial vehicle applications
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
name: SurePath AI
provenance_date: '2026-11-10'
provider_name: SurePath AI
provider_slug: surepath-ai
slug: surepath-ai-eligibility
source_date: '2026-11-10'
source_filename: surepath-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.surepath.ai/legal/software-subscription-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SurePath AI\naid: surepath-ai\nurl: https://www.surepath.ai/legal/software-subscription-agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: SurePath’s software-as-a-service platform designed to enable businesses to control access to, and enforce\n    corporate policy compliance applicable to, the business’s internal generative artificial intelligence (large\n    language model) use\n- type: individual\n  text: any individual or entity that accesses and uses the Subscription Services\nrestricted_uses:\n- summary: Export and sanctions\
  \ compliance\n  text: Customer affirms that it is not named on, owned by, or acting on behalf of any U.S. government denied-party\n    list\n- summary: Prohibited weapons and missile applications\n  text: used for any purposes prohibited by the Export Laws, including, but not limited to, nuclear, chemical, or\n    biological weapons proliferation, missile systems or technology, or restricted unmanned aerial vehicle applications\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/surepath-ai/eligibility/surepath-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from SurePath AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Governance
- AI Security
- Generative AI
- Enterprise AI
- Data Loss Prevention
- Compliance
---
