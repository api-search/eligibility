---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If You are using the Services as a Patient or individual (not a healthcare provider), You agree to the Acceptable Use Policy
    type: individual
  minimum_age:
    text: To comply with COPPA, doxy.me is not allowed to collect or store information from a minor.
    value: null
  restricted_uses:
  - summary: No medical, legal or professional advice
    text: As we are not a healthcare provider or legal firm, we cannot provide medical, professional, or legal advice.
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
name: Doxy.me
provenance_date: '2026-11-09'
provider_name: Doxy.me
provider_slug: doxy-me
slug: doxy-me-eligibility
source_date: '2026-11-09'
source_filename: doxy-me-eligibility.yml
source_heading: Eligibility
source_page: https://doxy.me/site/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Doxy.me\naid: doxy-me\nurl: https://doxy.me/site/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If You are using the Services as a Patient or individual (not a healthcare provider), You agree to the Acceptable\n    Use Policy\nrestricted_uses:\n- summary: No medical, legal or professional advice\n  text: As we are not a healthcare provider or legal firm, we cannot provide medical, professional, or legal advice.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ null\n  text: To comply with COPPA, doxy.me is not allowed to collect or store information from a minor.\n"
source_yaml_url: https://artifacts.apis.io/doxy-me/eligibility/doxy-me-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Doxy.me's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Telehealth
- Video
- HIPAA
- Free
- Secure
---
