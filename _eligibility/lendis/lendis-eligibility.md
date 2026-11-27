---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Die AGB gelten ausschließlich für den gewerblichen Bereich.
    type: business
  minimum_age:
    text: null
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
name: Lendis
provenance_date: '2026-11-09'
provider_name: Lendis
provider_slug: lendis
slug: lendis-eligibility
source_date: '2026-11-09'
source_filename: lendis-eligibility.yml
source_heading: Eligibility
source_page: https://www.lendis.io/agb/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lendis\naid: lendis\nurl: https://www.lendis.io/agb/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Die AGB gelten ausschließlich für den gewerblichen Bereich.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/lendis/eligibility/lendis-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Lendis's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Ai Enterprise Software
- Device As A Service
- IT Hardware
- Leasing
- Asset Management
- Workplace Technology
- Procurement
- Germany
- Software-as-a-Service
---
