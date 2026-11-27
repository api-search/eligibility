---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Access to and use of the Platform is limited exclusively to users located in states within the United States where the Platform is available. Services are not available to users located outside the UnitedStates.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not for emergencies
    text: Our Platform and the Services are not for medical emergencies or urgent situations.
  - summary: Personal use of prescriptions
    text: You agree that any prescriptions that you acquire from aProvider will be solely for your personal use.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Clarity Pediatrics, Medical Group, and your Provider may contact you by telephone, mail, or e-mail to verify your information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Claritypediatrics
provenance_date: '2026-11-09'
provider_name: Claritypediatrics
provider_slug: claritypediatrics
slug: claritypediatrics-eligibility
source_date: '2026-11-09'
source_filename: claritypediatrics-eligibility.yml
source_heading: Eligibility
source_page: https://www.claritypediatrics.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Claritypediatrics\naid: claritypediatrics\nurl: https://www.claritypediatrics.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Access to and use of the Platform is limited exclusively to users located in states within the United States\n    where the Platform is available. Services are not available to users located outside the UnitedStates.\nentity_types: []\nrestricted_uses:\n- summary: Not for emergencies\n  text: Our Platform and the Services are not for medical emergencies or urgent situations.\n- summary: Personal use of prescriptions\n  text: You agree\
  \ that any prescriptions that you acquire from aProvider will be solely for your personal use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Clarity Pediatrics, Medical Group, and your Provider may contact you by telephone, mail, or e-mail to verify\n    your information.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/claritypediatrics/eligibility/claritypediatrics-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Claritypediatrics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Telehealth
- Pediatrics
- Mental Health
- ADHD
- Digital Health
---
