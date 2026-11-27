---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Clinical decisions and medical advice not provided
    text: DeepScribe does not practice medicine or any other clinical profession, provide medical or other professional clinical advice, make diagnostic, treatment, coding, billing, or other clinical decisions
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
name: DeepScribe
provenance_date: '2026-11-09'
provider_name: DeepScribe
provider_slug: deepscribe
slug: deepscribe-eligibility
source_date: '2026-11-09'
source_filename: deepscribe-eligibility.yml
source_heading: Eligibility
source_page: https://www.deepscribe.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DeepScribe\naid: deepscribe\nurl: https://www.deepscribe.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Clinical decisions and medical advice not provided\n  text: DeepScribe does not practice medicine or any other clinical profession, provide medical or other professional\n    clinical advice, make diagnostic, treatment, coding, billing, or other clinical decisions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/deepscribe/eligibility/deepscribe-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from DeepScribe's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Clinical Documentation
- Medical Scribe
- Ambient AI
- Speech Recognition
- Medical Coding
- HIPAA
- EHR Integration
- Oncology
- Cardiology
- Value-Based Care
- Enterprise Saas
---
