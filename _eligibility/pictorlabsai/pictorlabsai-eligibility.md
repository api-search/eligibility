---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The letter must be signed personally by you or your legal guardian
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No clinical or diagnostic use
    text: may not be used for clinical purposes, including diagnosis or treatment of patients
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
name: PictorLabs.ai
provenance_date: '2026-11-10'
provider_name: PictorLabs.ai
provider_slug: pictorlabsai
slug: pictorlabsai-eligibility
source_date: '2026-11-10'
source_filename: pictorlabsai-eligibility.yml
source_heading: Eligibility
source_page: https://www.pictorlabs.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PictorLabs.ai\naid: pictorlabsai\nurl: https://www.pictorlabs.ai/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The letter must be signed personally by you or your legal guardian\nrestricted_uses:\n- summary: No clinical or diagnostic use\n  text: may not be used for clinical purposes, including diagnosis or treatment of patients\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pictorlabsai/eligibility/pictorlabsai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from PictorLabs.ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Digital Pathology
- Virtual Staining
- Histopathology
- Medical Imaging
- Healthcare
- Life Sciences
---
