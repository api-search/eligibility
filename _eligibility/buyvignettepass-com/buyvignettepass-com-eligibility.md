---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be legally able to enter a binding agreement in your jurisdiction.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful purposes only
    text: You may use the Service only for lawful purposes and in line with these Terms.
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
name: Buy Vignette Pass
provenance_date: '2026-11-09'
provider_name: Buy Vignette Pass
provider_slug: buyvignettepass-com
slug: buyvignettepass-com-eligibility
source_date: '2026-11-09'
source_filename: buyvignettepass-com-eligibility.yml
source_heading: Eligibility
source_page: https://buyvignettepass.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Buy Vignette Pass\naid: buyvignettepass-com\nurl: https://buyvignettepass.com/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be legally able to enter a binding agreement in your jurisdiction.\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You may use the Service only for lawful purposes and in line with these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/buyvignettepass-com/eligibility/buyvignettepass-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Buy Vignette Pass's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Toll
- Europe
- Travel
- Payments
---
