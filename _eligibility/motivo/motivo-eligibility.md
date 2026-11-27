---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: By using the Platform and/or Services, you acknowledge and agree that you are a United States resident with a valid United States address
  minimum_age:
    text: are at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: No medical advice
    text: the Services do not constitute medical advice or medical opinions
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
name: Motivo
provenance_date: '2026-11-10'
provider_name: Motivo
provider_slug: motivo
slug: motivo-eligibility
source_date: '2026-11-10'
source_filename: motivo-eligibility.yml
source_heading: Eligibility
source_page: https://motivohealth.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Motivo\naid: motivo\nurl: https://motivohealth.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: By using the Platform and/or Services, you acknowledge and agree that you are a United States resident with\n    a valid United States address\nentity_types: []\nrestricted_uses:\n- summary: No medical advice\n  text: the Services do not constitute medical advice or medical opinions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: are at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/motivo/eligibility/motivo-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Motivo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Behavioral Health
- Mental Health
- Clinical Supervision
- Healthcare Workforce
- Telehealth
- HIPAA
- Software-as-a-Service
---
