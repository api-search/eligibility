---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 16 or over, and the account is for you alone.
    type: individual
  minimum_age:
    text: You must be 16 or over, and the account is for you alone.
    value: '16'
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
name: arkerah
provenance_date: '2026-11-09'
provider_name: arkerah
provider_slug: arkerah-com
slug: arkerah-com-eligibility
source_date: '2026-11-09'
source_filename: arkerah-com-eligibility.yml
source_heading: Eligibility
source_page: https://arkerah.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: arkerah\naid: arkerah-com\nurl: https://arkerah.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be 16 or over, and the account is for you alone.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be 16 or over, and the account is for you alone.\n"
source_yaml_url: https://artifacts.apis.io/arkerah-com/eligibility/arkerah-com-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from arkerah's own page on 2026-11-09.
synthetic: false
tags:
- Job Matching
- Careers
- Europe
- Artificial Intelligence
---
