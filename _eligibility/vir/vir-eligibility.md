---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.
    type: individual
  minimum_age:
    text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.
    value: '18'
  restricted_uses:
  - summary: Not medical advice
    text: INFORMATION PRESENTED ON THE SITE IS INTENDED FOR INFORMATIONAL PURPOSES ONLY AND IS NOT PERSONALIZED MEDICAL DIAGNOSIS OR TREATMENT ADVICE.
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
name: Vir
provenance_date: '2026-11-10'
provider_name: Vir
provider_slug: vir
slug: vir-eligibility
source_date: '2026-11-10'
source_filename: vir-eligibility.yml
source_heading: Eligibility
source_page: https://www.vir.bio/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vir\naid: vir\nurl: https://www.vir.bio/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.\nrestricted_uses:\n- summary: Not medical advice\n  text: INFORMATION PRESENTED ON THE SITE IS INTENDED FOR INFORMATIONAL PURPOSES ONLY AND IS NOT PERSONALIZED MEDICAL\n    DIAGNOSIS OR TREATMENT ADVICE.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU MAY NOT ACCESS\
  \ OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.\n"
source_yaml_url: https://artifacts.apis.io/vir/eligibility/vir-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Vir's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health Tech
- Biotechnology
- Immunology
- Infectious Disease
- Oncology
- Pharmaceuticals
- Clinical Research
---
