---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years of age to use the Solution.
    type: individual
  minimum_age:
    text: You must be at least 13 years of age to use the Solution.
    value: '13'
  restricted_uses:
  - summary: Not a medical device or substitute for care
    text: The Solution is not a medical device, treatment, or substitute for professional medical care.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must create an account and provide accurate, current, and complete registration information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: NeuroFlow
provenance_date: '2026-11-10'
provider_name: NeuroFlow
provider_slug: neuroflow
slug: neuroflow-eligibility
source_date: '2026-11-10'
source_filename: neuroflow-eligibility.yml
source_heading: Eligibility
source_page: https://www.neuroflow.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NeuroFlow\naid: neuroflow\nurl: https://www.neuroflow.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years of age to use the Solution.\nrestricted_uses:\n- summary: Not a medical device or substitute for care\n  text: The Solution is not a medical device, treatment, or substitute for professional medical care.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must create an account and provide accurate, current, and complete registration information.\nminimum_age:\n\
  \  value: '13'\n  text: You must be at least 13 years of age to use the Solution.\n"
source_yaml_url: https://artifacts.apis.io/neuroflow/eligibility/neuroflow-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from NeuroFlow's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Behavioral Health
- Healthcare
- Mental Health
- Digital Health
- Care Coordination
- Health Analytics
- EHR Integration
---
