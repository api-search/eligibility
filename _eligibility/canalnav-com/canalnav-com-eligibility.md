---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be old enough to form a binding contract in your country to hold an account.
    value: null
  restricted_uses:
  - summary: Not for safety-critical decisions
    text: Canal Nav must not be used for safety-critical or emergency decisions
  - summary: No false safety information or impersonation
    text: Don’t submit false safety information or impersonate others.
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
name: Canal Nav
provenance_date: '2026-11-09'
provider_name: Canal Nav
provider_slug: canalnav-com
slug: canalnav-com-eligibility
source_date: '2026-11-09'
source_filename: canalnav-com-eligibility.yml
source_heading: Eligibility
source_page: https://canalnav.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Canal Nav\naid: canalnav-com\nurl: https://canalnav.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Not for safety-critical decisions\n  text: Canal Nav must not be used for safety-critical or emergency decisions\n- summary: No false safety information or impersonation\n  text: Don’t submit false safety information or impersonate others.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You must be old enough to form a binding contract in your country\
  \ to hold an account.\n"
source_yaml_url: https://artifacts.apis.io/canalnav-com/eligibility/canalnav-com-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Canal Nav's own page on 2026-11-09.
synthetic: false
tags:
- Navigation
- Boating
- UK Canals
- Route Planner
- Open Data
---
