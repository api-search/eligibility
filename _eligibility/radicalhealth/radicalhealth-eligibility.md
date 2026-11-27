---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Our Services are currently available only to residents of the United States.
  entity_types:
  - text: You must be at least 21 years of age and reside in the United States to use our Services.
    type: individual
  minimum_age:
    text: You must be at least 21 years of age and reside in the United States to use our Services.
    value: '21'
  restricted_uses:
  - summary: No medical advice to others
    text: Use the Services to provide medical advice to others.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Phone number verification is required during onboarding.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Radical Health
provenance_date: '2026-11-10'
provider_name: Radical Health
provider_slug: radicalhealth
slug: radicalhealth-eligibility
source_date: '2026-11-10'
source_filename: radicalhealth-eligibility.yml
source_heading: Eligibility
source_page: https://platform.radicalhealth.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Radical Health\naid: radicalhealth\nurl: https://platform.radicalhealth.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Our Services are currently available only to residents of the United States.\nentity_types:\n- type: individual\n  text: You must be at least 21 years of age and reside in the United States to use our Services.\nrestricted_uses:\n- summary: No medical advice to others\n  text: Use the Services to provide medical advice to others.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Phone number verification is required\
  \ during onboarding.\nminimum_age:\n  value: '21'\n  text: You must be at least 21 years of age and reside in the United States to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/radicalhealth/eligibility/radicalhealth-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Radical Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Oncology
- Artificial Intelligence
- Clinical Trials
- Patient Care
- Digital Health
---
