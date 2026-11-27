---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accepting this Agreement on behalf of a company or other legal entity, you represent that you have the authority to bind that entity.
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
name: Brivvy
provenance_date: '2026-11-09'
provider_name: Brivvy
provider_slug: brivvy-io
slug: brivvy-io-eligibility
source_date: '2026-11-09'
source_filename: brivvy-io-eligibility.yml
source_heading: Eligibility
source_page: https://brivvy.io/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brivvy\naid: brivvy-io\nurl: https://brivvy.io/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accepting this Agreement on behalf of a company or other legal entity, you represent that you\n    have the authority to bind that entity.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/brivvy-io/eligibility/brivvy-io-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Brivvy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Writing
- Marketing
- Collaboration
- Voice
- Software-as-a-Service
---
