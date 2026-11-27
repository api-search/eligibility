---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is intended solely for individuals who are at least 18 years of age or older.
    type: individual
  - text: or to your company or other entity if you are using the Service on behalf of such company or entity.
    type: business
  minimum_age:
    text: The Service is intended solely for individuals who are at least 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Violating the law
    text: Please don’t use this service to violate the law.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To access or use the Service, you must have a valid email address.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Tlon
provenance_date: '2026-11-10'
provider_name: Tlon
provider_slug: tlon-corporation
slug: tlon-corporation-eligibility
source_date: '2026-11-10'
source_filename: tlon-corporation-eligibility.yml
source_heading: Eligibility
source_page: https://tlon.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tlon\naid: tlon-corporation\nurl: https://tlon.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Service is intended solely for individuals who are at least 18 years of age or older.\n- type: business\n  text: or to your company or other entity if you are using the Service on behalf of such company or entity.\nrestricted_uses:\n- summary: Violating the law\n  text: Please don’t use this service to violate the law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To access or use the Service, you\
  \ must have a valid email address.\nminimum_age:\n  value: '18'\n  text: The Service is intended solely for individuals who are at least 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/tlon-corporation/eligibility/tlon-corporation-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Tlon's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Messaging
- Social
- Urbit
- Self-Hosting
- Decentralization
- Agents
- MCP
- Chat
- Hosting
---
