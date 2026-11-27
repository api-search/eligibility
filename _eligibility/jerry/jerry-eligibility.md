---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are at least 18 years of age and are a legal adult in the jurisdiction(s) in which you reside
    type: individual
  minimum_age:
    text: you are at least 18 years of age and are a legal adult in the jurisdiction(s) in which you reside
    value: '18'
  restricted_uses:
  - summary: Services for others
    text: the Services are offered only for your use, and not for the use or benefit of others;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You hereby authorize Jerry, directly or through third parties, to make any inquiries we consider necessary to validate your identity and/or to authenticate your identity and account information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Jerry
provenance_date: '2026-11-09'
provider_name: Jerry
provider_slug: jerry
slug: jerry-eligibility
source_date: '2026-11-09'
source_filename: jerry-eligibility.yml
source_heading: Eligibility
source_page: https://jerry.ai/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Jerry\naid: jerry\nurl: https://jerry.ai/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you are at least 18 years of age and are a legal adult in the jurisdiction(s) in which you reside\nrestricted_uses:\n- summary: Services for others\n  text: the Services are offered only for your use, and not for the use or benefit of others;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You hereby authorize Jerry, directly or through third parties, to make any inquiries we consider\
  \ necessary\n    to validate your identity and/or to authenticate your identity and account information.\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age and are a legal adult in the jurisdiction(s) in which you reside\n"
source_yaml_url: https://artifacts.apis.io/jerry/eligibility/jerry-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Jerry's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Insurtech
- Auto Insurance
- Insurance Broker
- Automotive
- Consumer Finance
- Lending
- Telematics
- Mobile App
- Artificial Intelligence
---
