---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Website is not intended for users outside of the United States. Access to the Website from countries where access to the Website would be considered unlawful is prohibited.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: AI model training or AI tool development
    text: use the SchoolAI Technology for the design, development, use or deployment of any software program or service, including but not limited to any purpose related to the training, testing, validating, or operating of any software or service incorporating a large language model
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
name: SchoolAI
provenance_date: '2026-11-10'
provider_name: SchoolAI
provider_slug: schoolai
slug: schoolai-eligibility
source_date: '2026-11-10'
source_filename: schoolai-eligibility.yml
source_heading: Eligibility
source_page: https://schoolai.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SchoolAI\naid: schoolai\nurl: https://schoolai.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Website is not intended for users outside of the United States. Access to the Website from countries\n    where access to the Website would be considered unlawful is prohibited.\nentity_types: []\nrestricted_uses:\n- summary: AI model training or AI tool development\n  text: use the SchoolAI Technology for the design, development, use or deployment of any software program or service,\n    including but not limited to any purpose related to the training, testing, validating,\
  \ or operating of any software\n    or service incorporating a large language model\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/schoolai/eligibility/schoolai-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from SchoolAI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Education
- EdTech
- Learning
- Teachers
- K-12
- Higher Education
---
