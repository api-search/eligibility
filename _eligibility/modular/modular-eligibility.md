---
claim_count: 7
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    served: []
    text: The U.S. government currently maintains comprehensive economic sanctions or an embargo against Cuba, Iran, North Korea, and the Crimea and other regions of Ukraine controlled by the Russian Federation.
  entity_types:
  - text: A User must be at least 18 years of age.
    type: individual
  - text: refer to the individual person, company, or organization that has visited or is using the Modular Platform
    type: business
  minimum_age:
    text: A User must be at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: High-risk activities
    text: You will not use the Modular Platform for high risk activities, where the use or failure of the Modular Platform could reasonably be expected to lead to death, personal injury, or environmental or property damage
  - summary: Prohibited sensitive data
    text: 'you will not submit to the Modular Platform: (a) protected health information regulated by the Health Insurance Portability and Accountability Act'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Account registration and provisioning is at Modular’s sole discretion
excluded_countries:
- CU
- IR
- KP
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Modular
provenance_date: '2026-11-10'
provider_name: Modular
provider_slug: modular
slug: modular-eligibility
source_date: '2026-11-10'
source_filename: modular-eligibility.yml
source_heading: Eligibility
source_page: https://www.modular.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Modular\naid: modular\nurl: https://www.modular.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  text: The U.S. government currently maintains comprehensive economic sanctions or an embargo against Cuba, Iran,\n    North Korea, and the Crimea and other regions of Ukraine controlled by the Russian Federation.\nentity_types:\n- type: individual\n  text: A User must be at least 18 years of age.\n- type: business\n  text: refer to the individual person, company, or organization that has visited or is using the Modular Platform\nrestricted_uses:\n- summary:\
  \ High-risk activities\n  text: You will not use the Modular Platform for high risk activities, where the use or failure of the Modular\n    Platform could reasonably be expected to lead to death, personal injury, or environmental or property damage\n- summary: Prohibited sensitive data\n  text: 'you will not submit to the Modular Platform: (a) protected health information regulated by the Health Insurance\n    Portability and Accountability Act'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Account registration and provisioning is at Modular’s sole discretion\nminimum_age:\n  value: '18'\n  text: A User must be at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/modular/eligibility/modular-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Modular's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Inference
- LLM
- GPU
- Developer Tools
- Infrastructure
---
