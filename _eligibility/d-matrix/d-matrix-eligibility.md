---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age to use the Site.
    type: individual
  - text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents and warrants that they have authority to bind you to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years of age to use the Site.
    value: '18'
  restricted_uses:
  - summary: Non-commercial use only
    text: solely for non-commercial purposes to learn more about our products and services and to review and apply for job openings
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
name: d-Matrix
provenance_date: '2026-11-09'
provider_name: d-Matrix
provider_slug: d-matrix
slug: d-matrix-eligibility
source_date: '2026-11-09'
source_filename: d-matrix-eligibility.yml
source_heading: Eligibility
source_page: https://www.d-matrix.ai/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: d-Matrix\naid: d-matrix\nurl: https://www.d-matrix.ai/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use the Site.\n- type: business\n  text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents\n    and warrants that they have authority to bind you to these Terms\nrestricted_uses:\n- summary: Non-commercial use only\n  text: solely for non-commercial purposes to learn more about our products and services and to review and\
  \ apply\n    for job openings\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Site.\n"
source_yaml_url: https://artifacts.apis.io/d-matrix/eligibility/d-matrix-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from d-Matrix's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Compute
- Artificial Intelligence
- Inference
- Hardware
- Accelerator
- Machine Learning
- Semiconductors
---
