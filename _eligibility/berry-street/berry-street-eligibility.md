---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The page does not list served or excluded countries; it refers to U.S. customers for arbitration and to users located outside the United States for emergency guidance.
  entity_types:
  - text: For other aspects, you must be at least 13 years of age (or such other minimum age at which you can provide consent to data processing under the laws of your territory)
    type: individual
  minimum_age:
    text: you must be at least 13 years of age (or such other minimum age at which you can provide consent to data processing under the laws of your territory)
    value: '13'
  restricted_uses:
  - summary: Not for emergencies
    text: USE OF THE SERVICES IS NOT FOR EMERGENCIES. IF YOU THINK YOU HAVE A MEDICAL EMERGENCY, CALL 911 OR GO TO THE NEAREST OPEN CLINIC OR EMERGENCY ROOM.
  - summary: Not for all medical conditions
    text: THE SERVICES ARE NOT APPROPRIATE FOR ALL MEDICAL CONDITIONS OR CONCERNS.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may also require identification verification.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Berry Street
provenance_date: '2026-11-09'
provider_name: Berry Street
provider_slug: berry-street
slug: berry-street-eligibility
source_date: '2026-11-09'
source_filename: berry-street-eligibility.yml
source_heading: Eligibility
source_page: https://www.berrystreet.co/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Berry Street\naid: berry-street\nurl: https://www.berrystreet.co/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The page does not list served or excluded countries; it refers to U.S. customers for arbitration and to\n    users located outside the United States for emergency guidance.\nentity_types:\n- type: individual\n  text: For other aspects, you must be at least 13 years of age (or such other minimum age at which you can provide\n    consent to data processing under the laws of your territory)\nrestricted_uses:\n- summary: Not for emergencies\n  text: USE\
  \ OF THE SERVICES IS NOT FOR EMERGENCIES. IF YOU THINK YOU HAVE A MEDICAL EMERGENCY, CALL 911 OR GO TO\n    THE NEAREST OPEN CLINIC OR EMERGENCY ROOM.\n- summary: Not for all medical conditions\n  text: THE SERVICES ARE NOT APPROPRIATE FOR ALL MEDICAL CONDITIONS OR CONCERNS.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may also require identification verification.\nminimum_age:\n  value: '13'\n  text: you must be at least 13 years of age (or such other minimum age at which you can provide consent to data\n    processing under the laws of your territory)\n"
source_yaml_url: https://artifacts.apis.io/berry-street/eligibility/berry-street-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Berry Street's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Nutrition
- Telehealth
- Dietitian
- Medical Nutrition Therapy
- Insurance
- Digital Health
---
