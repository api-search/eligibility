---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To use this website, you must be of legal age to form a binding contract with us under applicable law and meet all eligibility requirements.
    type: individual
  minimum_age:
    text: you must be of legal age to form a binding contract with us under applicable law
    value: null
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
name: apdf-io
provenance_date: '2026-11-09'
provider_name: apdf-io
provider_slug: apdf-io
slug: apdf-io-eligibility
source_date: '2026-11-09'
source_filename: apdf-io-eligibility.yml
source_heading: Eligibility
source_page: https://apdf.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: apdf-io\naid: apdf-io\nurl: https://apdf.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To use this website, you must be of legal age to form a binding contract with us under applicable law and\n    meet all eligibility requirements.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you must be of legal age to form a binding contract with us under applicable law\n"
source_yaml_url: https://artifacts.apis.io/apdf-io/eligibility/apdf-io-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from apdf-io's own page on 2026-11-09.
synthetic: false
tags:
- PDF
- Analytics
- Software-as-a-Service
- Engagement
---
