---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'Business (Custom): Custom limits, SSO, priority support, dedicated deployment'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal purposes
    text: Not use the service for illegal purposes
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
name: Rembr
provenance_date: '2026-11-10'
provider_name: Rembr
provider_slug: rembr
slug: rembr-eligibility
source_date: '2026-11-10'
source_filename: rembr-eligibility.yml
source_heading: Eligibility
source_page: https://rembr.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rembr\naid: rembr\nurl: https://rembr.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'Business (Custom): Custom limits, SSO, priority support, dedicated deployment'\nrestricted_uses:\n- summary: Illegal purposes\n  text: Not use the service for illegal purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rembr/eligibility/rembr-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Rembr's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Agents
- Memory
- Debugging
---
