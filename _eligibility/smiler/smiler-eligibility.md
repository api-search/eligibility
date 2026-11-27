---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: A consumer (natural person acting outside their business activity) has the right to withdraw from a contract concluded remotely within 14 days
    type: individual
  - text: '"Customer" means a natural or legal person who orders photography services through the Platform.'
    type: business
  minimum_age:
    text: 'Minimum age: 18 years. Persons under 18 may use the services only when accompanied by an adult.'
    value: '18'
  restricted_uses:
  - summary: No unlawful use
    text: The Customer must not use the Platform for any unlawful purpose, impersonate another person, or disrupt the Platform's operation.
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
name: Smiler
provenance_date: '2026-11-10'
provider_name: Smiler
provider_slug: smiler
slug: smiler-eligibility
source_date: '2026-11-10'
source_filename: smiler-eligibility.yml
source_heading: Eligibility
source_page: https://smiler.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Smiler\naid: smiler\nurl: https://smiler.co/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: A consumer (natural person acting outside their business activity) has the right to withdraw from a contract\n    concluded remotely within 14 days\n- type: business\n  text: '\"Customer\" means a natural or legal person who orders photography services through the Platform.'\nrestricted_uses:\n- summary: No unlawful use\n  text: The Customer must not use the Platform for any unlawful purpose, impersonate another person, or disrupt\n  \
  \  the Platform's operation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: 'Minimum age: 18 years. Persons under 18 may use the services only when accompanied by an adult.'\n"
source_yaml_url: https://artifacts.apis.io/smiler/eligibility/smiler-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Smiler's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Photography
- Marketplace
- Consumer
- Travel
- Booking
- Two-Sided Marketplace
- Netherlands
---
