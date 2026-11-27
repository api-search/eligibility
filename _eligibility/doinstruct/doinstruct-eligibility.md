---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The customer is an entrepreneur within the meaning of Section 14 para. 1 of the German Civil Code (BGB)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: AI feature limited to training purposes
    text: Customer may not upload content or use the AI feature for any purpose that is not directly related to trainings within the meaning of the contractual purpose.
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
name: doinstruct
provenance_date: '2026-11-09'
provider_name: doinstruct
provider_slug: doinstruct
slug: doinstruct-eligibility
source_date: '2026-11-09'
source_filename: doinstruct-eligibility.yml
source_heading: Eligibility
source_page: https://www.doinstruct.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: doinstruct\naid: doinstruct\nurl: https://www.doinstruct.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The customer is an entrepreneur within the meaning of Section 14 para. 1 of the German Civil Code (BGB)\nrestricted_uses:\n- summary: AI feature limited to training purposes\n  text: Customer may not upload content or use the AI feature for any purpose that is not directly related to trainings\n    within the meaning of the contractual purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/doinstruct/eligibility/doinstruct-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from doinstruct's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Training
- Compliance
- Frontline
- Learning
- Workforce
- Safety
- Artificial Intelligence
---
