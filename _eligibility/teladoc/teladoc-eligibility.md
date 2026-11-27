---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Teladoc Services can be accessed only from the United States unless specific program terms which apply to You expressly provide otherwise.
  entity_types:
  - text: a legally enforceable agreement between Teladoc and You, an individual
    type: individual
  minimum_age:
    text: You must be an adult of the legal age of majority or otherwise authorized under the laws in your jurisdiction or state of residence to enter into binding contracts.
    value: age of majority
  restricted_uses:
  - summary: Not for medical emergencies
    text: The Non-Advice Programs should not be used during a medical emergency or for the diagnosis or treatment of any medical condition.
  - summary: Non-advice programs
    text: do not offer medical advice, diagnosis or treatment and do not create a doctor-patient relationship between you and Teladoc
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
name: Teladoc
provenance_date: '2026-11-10'
provider_name: Teladoc
provider_slug: teladoc
slug: teladoc-eligibility
source_date: '2026-11-10'
source_filename: teladoc-eligibility.yml
source_heading: Eligibility
source_page: https://www.teladochealth.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Teladoc\naid: teladoc\nurl: https://www.teladochealth.com/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Teladoc Services can be accessed only from the United States unless specific program terms which apply\n    to You expressly provide otherwise.\nentity_types:\n- type: individual\n  text: a legally enforceable agreement between Teladoc and You, an individual\nrestricted_uses:\n- summary: Not for medical emergencies\n  text: The Non-Advice Programs should not be used during a medical emergency or for the diagnosis or treatment\n\
  \    of any medical condition.\n- summary: Non-advice programs\n  text: do not offer medical advice, diagnosis or treatment and do not create a doctor-patient relationship between\n    you and Teladoc\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: You must be an adult of the legal age of majority or otherwise authorized under the laws in your jurisdiction\n    or state of residence to enter into binding contracts.\n"
source_yaml_url: https://artifacts.apis.io/teladoc/eligibility/teladoc-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Teladoc's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health Tech
- Telehealth
- Virtual Care
- Healthcare
- Behavioral Health
- Webhook
- Mental Health
---
