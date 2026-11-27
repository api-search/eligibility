---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: YOU SHOULD BE AT LEAST 18 YEARS OF AGE TO ACCESS THE SITE.
    type: individual
  minimum_age:
    text: YOU SHOULD BE AT LEAST 18 YEARS OF AGE TO ACCESS THE SITE.
    value: '18'
  restricted_uses:
  - summary: Export control compliance
    text: You agree not to export, re-export, or transfer, directly or indirectly, any U.S. technical data acquired from Company, or any products utilizing such data, in violation of the United States export laws or regulations.
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
name: Digital Diagnostics
provenance_date: '2026-11-09'
provider_name: Digital Diagnostics
provider_slug: digital-diagnostics
slug: digital-diagnostics-eligibility
source_date: '2026-11-09'
source_filename: digital-diagnostics-eligibility.yml
source_heading: Eligibility
source_page: https://www.digitaldiagnostics.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Digital Diagnostics\naid: digital-diagnostics\nurl: https://www.digitaldiagnostics.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: YOU SHOULD BE AT LEAST 18 YEARS OF AGE TO ACCESS THE SITE.\nrestricted_uses:\n- summary: Export control compliance\n  text: You agree not to export, re-export, or transfer, directly or indirectly, any U.S. technical data acquired\n    from Company, or any products utilizing such data, in violation of the United States export laws or regulations.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU SHOULD BE AT LEAST 18 YEARS OF AGE TO ACCESS THE SITE.\n"
source_yaml_url: https://artifacts.apis.io/digital-diagnostics/eligibility/digital-diagnostics-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Digital Diagnostics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Artificial Intelligence
- Medical Diagnostics
- Diabetic Retinopathy
- Autonomous AI
- Ophthalmology
- Medical Devices
---
