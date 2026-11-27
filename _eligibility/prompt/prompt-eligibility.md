---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This Site is controlled and operated in the United States and is intended for users located in the U.S.
  entity_types:
  - text: To use the Site solely for your internal business purposes;
    type: business
  minimum_age:
    text: That you are at least the age of majority in your state of residence and are legally capable of entering into a binding contract;
    value: age of majority in state of residence
  restricted_uses:
  - summary: No medical advice or diagnosis via Site
    text: Not use this Site to seek, provide, or obtain specific medical advice, medical opinion, diagnosis or treatment as applied to a patient’s particular condition or situation;
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
name: Prompt
provenance_date: '2026-11-10'
provider_name: Prompt
provider_slug: prompt
slug: prompt-eligibility
source_date: '2026-11-10'
source_filename: prompt-eligibility.yml
source_heading: Eligibility
source_page: https://www.prompthealth.com/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Prompt\naid: prompt\nurl: https://www.prompthealth.com/legal/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This Site is controlled and operated in the United States and is intended for users located in the U.S.\nentity_types:\n- type: business\n  text: To use the Site solely for your internal business purposes;\nrestricted_uses:\n- summary: No medical advice or diagnosis via Site\n  text: Not use this Site to seek, provide, or obtain specific medical advice, medical opinion, diagnosis or treatment\n    as applied to a patient’s particular condition or\
  \ situation;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority in state of residence\n  text: That you are at least the age of majority in your state of residence and are legally capable of entering\n    into a binding contract;\n"
source_yaml_url: https://artifacts.apis.io/prompt/eligibility/prompt-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Prompt's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Electronic Health Records
- Practice Management
- Physical Therapy
- Rehabilitation Therapy
- Health IT
- Medical Billing
- Patient Engagement
- Artificial Intelligence
---
