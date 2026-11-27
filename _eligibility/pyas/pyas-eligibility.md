---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This Service is provided exclusively to individuals and businesses.
    type: individual
  - text: This Service is provided exclusively to individuals and businesses.
    type: business
  minimum_age:
    text: To use Pyas, you must be at least 18 years old and have a valid email address.
    value: '18'
  restricted_uses:
  - summary: Unlawful or prohibited activities
    text: You agree to not use this Service for any unlawful or prohibited activities.
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
name: BrutForce Technologies
provenance_date: '2026-11-10'
provider_name: BrutForce Technologies
provider_slug: pyas
slug: pyas-eligibility
source_date: '2026-11-10'
source_filename: pyas-eligibility.yml
source_heading: Eligibility
source_page: https://pyas.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BrutForce Technologies\naid: pyas\nurl: https://pyas.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: This Service is provided exclusively to individuals and businesses.\n- type: business\n  text: This Service is provided exclusively to individuals and businesses.\nrestricted_uses:\n- summary: Unlawful or prohibited activities\n  text: You agree to not use this Service for any unlawful or prohibited activities.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n \
  \ text: To use Pyas, you must be at least 18 years old and have a valid email address.\n"
source_yaml_url: https://artifacts.apis.io/pyas/eligibility/pyas-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from BrutForce Technologies's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Calendar
- Integration
- Startups
- Software-as-a-Service
---
