---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age to use the Site.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to use the Site.
    value: '18'
  restricted_uses:
  - summary: Non-commercial use only
    text: solely for non-commercial purposes to learn more about BardyDx products and services
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
name: Bardy Diagnostics
provenance_date: '2026-11-09'
provider_name: Bardy Diagnostics
provider_slug: bardy-diagnostics
slug: bardy-diagnostics-eligibility
source_date: '2026-11-09'
source_filename: bardy-diagnostics-eligibility.yml
source_heading: Eligibility
source_page: https://www.bardydx.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bardy Diagnostics\naid: bardy-diagnostics\nurl: https://www.bardydx.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use the Site.\nrestricted_uses:\n- summary: Non-commercial use only\n  text: solely for non-commercial purposes to learn more about BardyDx products and services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Site.\n"
source_yaml_url: https://artifacts.apis.io/bardy-diagnostics/eligibility/bardy-diagnostics-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Bardy Diagnostics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Cardiology
- Diagnostics
- Remote Monitoring
---
