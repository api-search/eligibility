---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You agree that you will not use the Website or create an account unless you are at least 13 years of age.
    value: '13'
  restricted_uses:
  - summary: Not for medical emergencies
    text: The Website is not intended for medical emergencies or urgent situations.
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
name: Commons Clinic
provenance_date: '2026-11-09'
provider_name: Commons Clinic
provider_slug: commons-clinic
slug: commons-clinic-eligibility
source_date: '2026-11-09'
source_filename: commons-clinic-eligibility.yml
source_heading: Eligibility
source_page: https://commonsclinic.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Commons Clinic\naid: commons-clinic\nurl: https://commonsclinic.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Not for medical emergencies\n  text: The Website is not intended for medical emergencies or urgent situations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You agree that you will not use the Website or create an account unless you are at least 13 years of age.\n"
source_yaml_url: https://artifacts.apis.io/commons-clinic/eligibility/commons-clinic-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Commons Clinic's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Orthopedics
- Spine
- Sports Medicine
- Musculoskeletal
- Physical Therapy
- Surgery
- Pain Management
- Preventive Health
- Clinics
---
