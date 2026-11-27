---
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - GB
    served: []
    text: You are not accessing the services from the United Kingdom or the European Union, and are not a citizen subject to the laws of the United Kingdom or the European Union.
  entity_types:
  - text: Our Services are limited to individuals who meet certain criteria and can make certain promises
    type: individual
  minimum_age:
    text: You're 18+ years old;
    value: '18'
  restricted_uses:
  - summary: Synthetic or hypothetical data only
    text: The GenHealth Services and API are provided for beta testing purposes only and are to only be used with hypothetical or synthetic patient data.
  - summary: Informational use, not medical advice
    text: The information provided to you is for informational purposes only and not for treatment, and that you must always consult your physician with regard to any medical advice, diagnosis, or other medical suggestions
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You have provided us with your legal name and you are the person you purport to be
excluded_countries:
- GB
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: GenHealth.ai
provenance_date: '2026-11-09'
provider_name: GenHealth.ai
provider_slug: genhealthai
slug: genhealthai-eligibility
source_date: '2026-11-09'
source_filename: genhealthai-eligibility.yml
source_heading: Eligibility
source_page: https://genhealth.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GenHealth.ai\naid: genhealthai\nurl: https://genhealth.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - GB\n  text: You are not accessing the services from the United Kingdom or the European Union, and are not a citizen\n    subject to the laws of the United Kingdom or the European Union.\nentity_types:\n- type: individual\n  text: Our Services are limited to individuals who meet certain criteria and can make certain promises\nrestricted_uses:\n- summary: Synthetic or hypothetical data only\n  text: The GenHealth Services and API are provided for beta testing purposes only and are\
  \ to only be used with\n    hypothetical or synthetic patient data.\n- summary: Informational use, not medical advice\n  text: The information provided to you is for informational purposes only and not for treatment, and that you must\n    always consult your physician with regard to any medical advice, diagnosis, or other medical suggestions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You have provided us with your legal name and you are the person you purport to be\nminimum_age:\n  value: '18'\n  text: You're 18+ years old;\n"
source_yaml_url: https://artifacts.apis.io/genhealthai/eligibility/genhealthai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from GenHealth.ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Artificial Intelligence
- Generative AI
- Prior Authorization
- Revenue Cycle Management
- FHIR
- HL7 Da Vinci
- Medical Coding
- Utilization Management
---
