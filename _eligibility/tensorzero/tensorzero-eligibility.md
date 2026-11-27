---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF THE INDIVIDUAL ACCEPTING THIS AGREEMENT IS ACCEPTING ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY
    type: business
  - text: if Customer is an agency of the US Government or any contractor therefor
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: PHI requires executed BAA
    text: Customer is expressly prohibited from providing, uploading, submitting, or otherwise processing any PHI through the Services in the absence of an executed BAA.
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
name: TensorZero
provenance_date: '2026-11-10'
provider_name: TensorZero
provider_slug: tensorzero
slug: tensorzero-eligibility
source_date: '2026-11-10'
source_filename: tensorzero-eligibility.yml
source_heading: Eligibility
source_page: https://www.tensorzero.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TensorZero\naid: tensorzero\nurl: https://www.tensorzero.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF THE INDIVIDUAL ACCEPTING THIS AGREEMENT IS ACCEPTING ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY\n- type: government\n  text: if Customer is an agency of the US Government or any contractor therefor\nrestricted_uses:\n- summary: PHI requires executed BAA\n  text: Customer is expressly prohibited from providing, uploading, submitting, or otherwise processing any PHI\n    through the Services in the absence of an executed\
  \ BAA.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tensorzero/eligibility/tensorzero-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from TensorZero's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- LLM
- LLMOps
- AI Gateway
- Inference
- Observability
- Open Source
- Model Routing
---
