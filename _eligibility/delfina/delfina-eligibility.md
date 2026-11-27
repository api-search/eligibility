---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a “terrorist supporting” country
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No emergency use
    text: In the event of an emergency, a Medical Provider will not be alerted or notified.
  - summary: Not a substitute for medical advice or contraception
    text: the Platform and the Services are not intended to replace professional medical advice or diagnose, treat or manage any illness or medical condition, or serve as a birth control method or contraception.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You are required to create an account in order to use the Platform
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Delfina
provenance_date: '2026-11-09'
provider_name: Delfina
provider_slug: delfina
slug: delfina-eligibility
source_date: '2026-11-09'
source_filename: delfina-eligibility.yml
source_heading: Eligibility
source_page: https://www.delfina.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Delfina\naid: delfina\nurl: https://www.delfina.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are not located in a country that is subject to a U.S. Government embargo, or that has been designated\n    by the U.S. Government as a “terrorist supporting” country\nentity_types: []\nrestricted_uses:\n- summary: No emergency use\n  text: In the event of an emergency, a Medical Provider will not be alerted or notified.\n- summary: Not a substitute for medical advice or contraception\n  text: the Platform and the Services are not intended to replace professional\
  \ medical advice or diagnose, treat\n    or manage any illness or medical condition, or serve as a birth control method or contraception.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You are required to create an account in order to use the Platform\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/delfina/eligibility/delfina-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Delfina's own page on 2026-11-09.
synthetic: false
tags:
- Maternal Health
- Pregnancy Care
- Digital Health
- Remote Patient Monitoring
- Telehealth
- Health Plans
- Employer Benefits
- HIPAA
- SOC 2
---
