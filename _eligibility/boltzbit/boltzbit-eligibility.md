---
claim_count: 2
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
  - summary: High Risk Activities
    text: “High Risk Activities” means any activities defined as prohibited artificial intelligence practice or as high-risk uses of artificial intelligence systems under European artificial intelligence legislation or any similar classification or designation under Applicable Laws.
  - summary: ITAR-controlled data
    text: (iii) to create, transmit, process, or store any Customer Data that is subject to the International Traffic in Arms Regulations;
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
name: Boltzbit
provenance_date: '2026-11-09'
provider_name: Boltzbit
provider_slug: boltzbit
slug: boltzbit-eligibility
source_date: '2026-11-09'
source_filename: boltzbit-eligibility.yml
source_heading: Eligibility
source_page: https://boltzbit.com/terms-of-services-commercial
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Boltzbit\naid: boltzbit\nurl: https://boltzbit.com/terms-of-services-commercial\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: High Risk Activities\n  text: “High Risk Activities” means any activities defined as prohibited artificial intelligence practice or as\n    high-risk uses of artificial intelligence systems under European artificial intelligence legislation or any\n    similar classification or designation under Applicable Laws.\n- summary: ITAR-controlled data\n  text: (iii) to create, transmit, process, or store any\
  \ Customer Data that is subject to the International Traffic\n    in Arms Regulations;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/boltzbit/eligibility/boltzbit-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Boltzbit's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- LLM
- Generative AI
- Enterprise AI
- Model Fine-Tuning
- MLOps
---
