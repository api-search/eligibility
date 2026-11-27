---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You warrant and represent to Recce that you are able to enter into contracts by any and all applicable laws and regulations.
    type: individual
  - text: you warrant and represent that you have the authority to bind that entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Competitive product use
    text: use the Services in violation of any applicable law or regulation, in order to build a competitive product or service
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
name: InfuseAI
provenance_date: '2026-11-09'
provider_name: InfuseAI
provider_slug: infuseai-io
slug: infuseai-io-eligibility
source_date: '2026-11-09'
source_filename: infuseai-io-eligibility.yml
source_heading: Eligibility
source_page: https://reccehq.com/statements/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: InfuseAI\naid: infuseai-io\nurl: https://reccehq.com/statements/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You warrant and represent to Recce that you are able to enter into contracts by any and all applicable laws\n    and regulations.\n- type: business\n  text: you warrant and represent that you have the authority to bind that entity\nrestricted_uses:\n- summary: Competitive product use\n  text: use the Services in violation of any applicable law or regulation, in order to build a competitive product\n    or service\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/infuseai-io/eligibility/infuseai-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from InfuseAI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- DataReview
- CI/CD
- Data Quality
---
