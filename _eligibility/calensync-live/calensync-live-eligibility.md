---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Only humans may register accounts.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sensitive information
    text: Sensitive information must not be sent to the company where unauthorised disclosure could cause significant harm.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must use a valid Google account to signup and login
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Calensync
provenance_date: '2026-11-09'
provider_name: Calensync
provider_slug: calensync-live
slug: calensync-live-eligibility
source_date: '2026-11-09'
source_filename: calensync-live-eligibility.yml
source_heading: Eligibility
source_page: https://calensync.live/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Calensync\naid: calensync-live\nurl: https://calensync.live/tos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Only humans may register accounts.\nrestricted_uses:\n- summary: Sensitive information\n  text: Sensitive information must not be sent to the company where unauthorised disclosure could cause significant\n    harm.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must use a valid Google account to signup and login\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/calensync-live/eligibility/calensync-live-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Calensync's own page on 2026-11-09.
synthetic: false
tags:
- Calendar
- Sync
- Automation
- Software-as-a-Service
- Productivity
---
