---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: When the user of the Website or Services is an organization, the person who registers for an account will be deemed as the administrator of the organization account
    type: other
  minimum_age:
    text: You represent that by using the Service, you are at least eighteen (18) years of age.
    value: '18'
  restricted_uses:
  - summary: Not for emergency medical needs
    text: DO NOT USE THIS SERVICE FOR EMERGENCY MEDICAL NEEDS.
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
name: QT Medical
provenance_date: '2026-11-10'
provider_name: QT Medical
provider_slug: qt-medical
slug: qt-medical-eligibility
source_date: '2026-11-10'
source_filename: qt-medical-eligibility.yml
source_heading: Eligibility
source_page: https://www.qtmedical.com/en/term
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: QT Medical\naid: qt-medical\nurl: https://www.qtmedical.com/en/term\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: When the user of the Website or Services is an organization, the person who registers for an account will\n    be deemed as the administrator of the organization account\nrestricted_uses:\n- summary: Not for emergency medical needs\n  text: DO NOT USE THIS SERVICE FOR EMERGENCY MEDICAL NEEDS.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent\
  \ that by using the Service, you are at least eighteen (18) years of age.\n"
source_yaml_url: https://artifacts.apis.io/qt-medical/eligibility/qt-medical-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from QT Medical's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Medical Devices
- ECG
- Cardiology
- Remote Patient Monitoring
- Telehealth
- HIPAA
- Digital Health
---
