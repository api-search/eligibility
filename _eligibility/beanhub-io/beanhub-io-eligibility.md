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
  - summary: US sanctions
    text: You may not use the Services if such use is inconsistent with U.S. sanctions law or if you are on any list maintained by a U.S. government authority relating to designated, restricted or prohibited persons.
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
name: BeanHub
provenance_date: '2026-11-09'
provider_name: BeanHub
provider_slug: beanhub-io
slug: beanhub-io-eligibility
source_date: '2026-11-09'
source_filename: beanhub-io-eligibility.yml
source_heading: Eligibility
source_page: https://beanhub.io/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BeanHub\naid: beanhub-io\nurl: https://beanhub.io/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: US sanctions\n  text: You may not use the Services if such use is inconsistent with U.S. sanctions law or if you are on any list\n    maintained by a U.S. government authority relating to designated, restricted or prohibited persons.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/beanhub-io/eligibility/beanhub-io-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from BeanHub's own page on 2026-11-09.
synthetic: false
tags:
- Accounting
- Software-as-a-Service
- Open Source
- Finance
- Bookkeeping
- Developer Tools
- Company
---
