---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: They apply to both individual and organizational users.
    type: individual
  - text: Our services are subscription-based and intended for internal business purposes.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk activities prohibited
    text: Use the platform for high-risk activities
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
name: Rivio
provenance_date: '2026-11-10'
provider_name: Rivio
provider_slug: rivio
slug: rivio-eligibility
source_date: '2026-11-10'
source_filename: rivio-eligibility.yml
source_heading: Eligibility
source_page: https://www.rivio.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rivio\naid: rivio\nurl: https://www.rivio.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: They apply to both individual and organizational users.\n- type: business\n  text: Our services are subscription-based and intended for internal business purposes.\nrestricted_uses:\n- summary: High-risk activities prohibited\n  text: Use the platform for high-risk activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rivio/eligibility/rivio-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Rivio's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Procurement
- Software-as-a-Service
- B2B
- Automation
---
