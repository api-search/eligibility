---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You hereby certify that you are physically located in the State you have entered as your current location on the Services.
  minimum_age:
    text: you represent and warrant that you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Not for emergency medical needs
    text: DO NOT USE THE SERVICES OR THIS WEBSITE FOR EMERGENCY MEDICAL NEEDS. IF YOU EXPERIENCE A MEDICAL EMERGENCY, CALL 9-1-1 IMMEDIATELY.
  - summary: Medicare/Medicaid fee-for-service beneficiaries excluded
    text: You hereby certify that you are not a fee-for-service Medicare or Medicaid beneficiary.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You hereby certify that you are physically located in the State you have entered as your current location on the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Curve Health
provenance_date: '2026-11-09'
provider_name: Curve Health
provider_slug: curve-health
slug: curve-health-eligibility
source_date: '2026-11-09'
source_filename: curve-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.curvehealth.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Curve Health\naid: curve-health\nurl: https://www.curvehealth.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You hereby certify that you are physically located in the State you have entered as your current location\n    on the Services.\nentity_types: []\nrestricted_uses:\n- summary: Not for emergency medical needs\n  text: DO NOT USE THE SERVICES OR THIS WEBSITE FOR EMERGENCY MEDICAL NEEDS. IF YOU EXPERIENCE A MEDICAL EMERGENCY,\n    CALL 9-1-1 IMMEDIATELY.\n- summary: Medicare/Medicaid fee-for-service beneficiaries excluded\n  text: You hereby certify that you\
  \ are not a fee-for-service Medicare or Medicaid beneficiary.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You hereby certify that you are physically located in the State you have entered as your current location\n    on the Services.\nminimum_age:\n  value: '18'\n  text: you represent and warrant that you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/curve-health/eligibility/curve-health-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Curve Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Telehealth
- Digital Health
- Senior Care
- Skilled Nursing
- Health Information Exchange
- Predictive Analytics
---
