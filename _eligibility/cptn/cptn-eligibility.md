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
  - summary: Unlawful or harmful material
    text: use this website or its associated services to transmit or publish any harassing, indecent, obscene, fraudulent, or unlawful material
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
name: DevRaven
provenance_date: '2026-11-09'
provider_name: DevRaven
provider_slug: cptn
slug: cptn-eligibility
source_date: '2026-11-09'
source_filename: cptn-eligibility.yml
source_heading: Eligibility
source_page: https://cptn.io/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DevRaven\naid: cptn\nurl: https://cptn.io/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or harmful material\n  text: use this website or its associated services to transmit or publish any harassing, indecent, obscene, fraudulent,\n    or unlawful material\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cptn/eligibility/cptn-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from DevRaven's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Integration
- Open Source
- Data Pipeline
- Automation
---
