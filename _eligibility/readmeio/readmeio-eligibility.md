---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 13 years or older to use ReadMe.
    type: individual
  minimum_age:
    text: You must be 13 years or older to use ReadMe.
    value: '13'
  restricted_uses:
  - summary: Illegal or unauthorized purpose
    text: You may not use ReadMe for illegal or unauthorized purpose.
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
name: ReadMe.io
provenance_date: '2026-11-10'
provider_name: ReadMe.io
provider_slug: readmeio
slug: readmeio-eligibility
source_date: '2026-11-10'
source_filename: readmeio-eligibility.yml
source_heading: Eligibility
source_page: https://readme.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ReadMe.io\naid: readmeio\nurl: https://readme.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be 13 years or older to use ReadMe.\nrestricted_uses:\n- summary: Illegal or unauthorized purpose\n  text: You may not use ReadMe for illegal or unauthorized purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be 13 years or older to use ReadMe.\n"
source_yaml_url: https://artifacts.apis.io/readmeio/eligibility/readmeio-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from ReadMe.io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Documentation
- API Documentation
- Developer Experience
- Developer Portal
- OpenAPI
- Developer Hub
- API Metrics
---
