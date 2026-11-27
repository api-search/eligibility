---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Glucommander® is only available for use in the United States. This site is only intended for use in the United States.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not a substitute for medical advice
    text: This information is not intended to be a substitute for the advice provided by a physician or other medical professional.
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
name: Glytec
provenance_date: '2026-11-09'
provider_name: Glytec
provider_slug: glytec
slug: glytec-eligibility
source_date: '2026-11-09'
source_filename: glytec-eligibility.yml
source_heading: Eligibility
source_page: https://glytec.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Glytec\naid: glytec\nurl: https://glytec.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Glucommander® is only available for use in the United States. This site is only intended for use in the\n    United States.\nentity_types: []\nrestricted_uses:\n- summary: Not a substitute for medical advice\n  text: This information is not intended to be a substitute for the advice provided by a physician or other medical\n    professional.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/glytec/eligibility/glytec-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Glytec's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Health IT
- Clinical Decision Support
- Diabetes
- Insulin Management
- glycemic-management
- Hospitals
- EHR Integration
- HL7
- Medical Devices
- Software as a Medical Device
---
