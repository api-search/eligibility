---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Only individuals 13 years of age or older may use the Site or our services.
    type: individual
  minimum_age:
    text: Only individuals 13 years of age or older may use the Site or our services.
    value: '13'
  restricted_uses:
  - summary: Non-commercial personal viewing only
    text: for personal, non-commercial transitory viewing only
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
name: Sibel Health
provenance_date: '2026-11-10'
provider_name: Sibel Health
provider_slug: sibel-health
slug: sibel-health-eligibility
source_date: '2026-11-10'
source_filename: sibel-health-eligibility.yml
source_heading: Eligibility
source_page: https://sibelhealth.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sibel Health\naid: sibel-health\nurl: https://sibelhealth.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Only individuals 13 years of age or older may use the Site or our services.\nrestricted_uses:\n- summary: Non-commercial personal viewing only\n  text: for personal, non-commercial transitory viewing only\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Only individuals 13 years of age or older may use the Site or our services.\n"
source_yaml_url: https://artifacts.apis.io/sibel-health/eligibility/sibel-health-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Sibel Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Medical Devices
- Remote Patient Monitoring
- Wearables
- Digital Health
- Vital Signs
- Clinical Trials
- Sensors
- IoT
- Sleep
---
