---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Sensely controls and operates this Site from its headquarters in the United States of America and the Materials may not be appropriate or available for use in other locations.
  entity_types:
  - text: If you are using this Site on behalf of a company, you represent that you are authorized to legally bind the company to these Terms.
    type: business
  minimum_age:
    text: If you are between the ages of 13 and 18, you may use the Site with the permission of your parent or legal guardian. Patients under 13 may not use the Services.
    value: '13'
  restricted_uses:
  - summary: Not for emergency medical needs
    text: Do not use our Services or mobile applications or this Site for emergency medical needs.
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
name: Sensely
provenance_date: '2026-11-10'
provider_name: Sensely
provider_slug: sensely
slug: sensely-eligibility
source_date: '2026-11-10'
source_filename: sensely-eligibility.yml
source_heading: Eligibility
source_page: https://sensely.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sensely\naid: sensely\nurl: https://sensely.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Sensely controls and operates this Site from its headquarters in the United States of America and the Materials\n    may not be appropriate or available for use in other locations.\nentity_types:\n- type: business\n  text: If you are using this Site on behalf of a company, you represent that you are authorized to legally bind\n    the company to these Terms.\nrestricted_uses:\n- summary: Not for emergency medical needs\n  text: Do not use our Services or mobile applications\
  \ or this Site for emergency medical needs.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: If you are between the ages of 13 and 18, you may use the Site with the permission of your parent or legal\n    guardian. Patients under 13 may not use the Services.\n"
source_yaml_url: https://artifacts.apis.io/sensely/eligibility/sensely-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Sensely's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Digital Health
- Conversational AI
- Virtual Assistant
- Symptom Checker
- Patient Engagement
- Health Insurance
- Mental Health
- SDK
---
