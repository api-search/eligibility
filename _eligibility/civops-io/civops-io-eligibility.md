---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18, or the age of majority where you live, to buy.
    type: individual
  minimum_age:
    text: You must be at least 18, or the age of majority where you live, to buy.
    value: '18'
  restricted_uses:
  - summary: Acceptable use limits
    text: 'Do not use our products or site to: break the law, or anyone else''s rights;'
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
name: civops-io
provenance_date: '2026-11-09'
provider_name: civops-io
provider_slug: civops-io
slug: civops-io-eligibility
source_date: '2026-11-09'
source_filename: civops-io-eligibility.yml
source_heading: Eligibility
source_page: https://civops.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: civops-io\naid: civops-io\nurl: https://civops.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18, or the age of majority where you live, to buy.\nrestricted_uses:\n- summary: Acceptable use limits\n  text: 'Do not use our products or site to: break the law, or anyone else''s rights;'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18, or the age of majority where you live, to buy.\n"
source_yaml_url: https://artifacts.apis.io/civops-io/eligibility/civops-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from civops-io's own page on 2026-11-09.
synthetic: false
tags:
- Manufacturing Software
- AI Platform
- Operational Analytics
- Contractor Management
---
