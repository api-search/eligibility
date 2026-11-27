---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are intended for use by individuals at least the age majority in their jurisdiction.
    type: individual
  - text: you have sufficient right to bind such third party to these Terms
    type: business
  minimum_age:
    text: To register for an Account (as defined below) on the Services you must be 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: No commercial endeavors
    text: (c) use the Services in connection with any commercial endeavors
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
name: Uplight
provenance_date: '2026-11-10'
provider_name: Uplight
provider_slug: uplight
slug: uplight-eligibility
source_date: '2026-11-10'
source_filename: uplight-eligibility.yml
source_heading: Eligibility
source_page: https://uplight.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Uplight\naid: uplight\nurl: https://uplight.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Services are intended for use by individuals at least the age majority in their jurisdiction.\n- type: business\n  text: you have sufficient right to bind such third party to these Terms\nrestricted_uses:\n- summary: No commercial endeavors\n  text: (c) use the Services in connection with any commercial endeavors\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: To register for an Account (as defined below) on the Services you must be 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/uplight/eligibility/uplight-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Uplight's own page on 2026-11-10.
synthetic: false
tags:
- Energy
- United States
- Utilities
- Electricity
- Gas
- Demand Response
- DER
- Grid
- Virtual Power Plant
- DERMS
- Energy Efficiency
- Customer Engagement
---
