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
  - summary: Site information is not medical advice
    text: is not meant to give medical advice, provide a diagnosis and more generally to be a substitute for advice provided by a doctor or other qualified health care professional.
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
name: Brainever
provenance_date: '2026-11-09'
provider_name: Brainever
provider_slug: brainever
slug: brainever-eligibility
source_date: '2026-11-09'
source_filename: brainever-eligibility.yml
source_heading: Eligibility
source_page: https://brainever.fr/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brainever\naid: brainever\nurl: https://brainever.fr/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Site information is not medical advice\n  text: is not meant to give medical advice, provide a diagnosis and more generally to be a substitute for advice\n    provided by a doctor or other qualified health care professional.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/brainever/eligibility/brainever-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Brainever's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Biopharma
- Neurodegenerative
- Homeoprotein
- ALS
- Parkinson
---
