---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You may only use the Website Services within the United States, unless otherwise permitted by applicable law.
  entity_types:
  - text: If you are accessing or using our Website Services on behalf of another person or entity, you represent that you are authorized to accept these Terms on that person or entity’s behalf
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not for medical emergencies
    text: THE WEBSITE SERVICES ARE NOT FOR USE IN MEDICAL EMERGENCIES OR OTHER URGENT SITUATIONS.
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
name: Array Behavioral Care
provenance_date: '2026-11-09'
provider_name: Array Behavioral Care
provider_slug: array-behavioral-care
slug: array-behavioral-care-eligibility
source_date: '2026-11-09'
source_filename: array-behavioral-care-eligibility.yml
source_heading: Eligibility
source_page: https://arraybc.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Array Behavioral Care\naid: array-behavioral-care\nurl: https://arraybc.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You may only use the Website Services within the United States, unless otherwise permitted by applicable\n    law.\nentity_types:\n- type: business\n  text: If you are accessing or using our Website Services on behalf of another person or entity, you represent\n    that you are authorized to accept these Terms on that person or entity’s behalf\nrestricted_uses:\n- summary: Not for medical emergencies\n  text: THE WEBSITE SERVICES ARE NOT FOR\
  \ USE IN MEDICAL EMERGENCIES OR OTHER URGENT SITUATIONS.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/array-behavioral-care/eligibility/array-behavioral-care-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Array Behavioral Care's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Behavioral Health
- Mental Health
- Telehealth
- Telepsychiatry
- Digital Health
- Electronic Health Records
- Patient Engagement
- HIPAA
---
