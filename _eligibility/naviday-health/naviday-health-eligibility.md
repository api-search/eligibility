---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to create an account. If you are under 18, you may use LUCI with parental or guardian consent.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to create an account.
    value: '18'
  restricted_uses:
  - summary: Unlawful purposes
    text: Use LUCI for any unlawful purpose
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
name: Naviday Health
provenance_date: '2026-11-10'
provider_name: Naviday Health
provider_slug: naviday-health
slug: naviday-health-eligibility
source_date: '2026-11-10'
source_filename: naviday-health-eligibility.yml
source_heading: Eligibility
source_page: https://navidayhealth.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Naviday Health\naid: naviday-health\nurl: https://navidayhealth.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to create an account. If you are under 18, you may use LUCI with parental\n    or guardian consent.\nrestricted_uses:\n- summary: Unlawful purposes\n  text: Use LUCI for any unlawful purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to create an account.\n"
source_yaml_url: https://artifacts.apis.io/naviday-health/eligibility/naviday-health-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Naviday Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Women's Health
- Digital Health
- Wearables
- Clinical Decision Support
- Health Tech
---
