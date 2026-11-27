---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: an individual end user (“You” “Your”) of the Green Dot developer portal website
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Blocking for suspected violations
    text: If Green Dot suspects that You have violated the requirements of this Section, Green Dot may block Your access to the Site without advanced notice
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
name: Green Dot
provenance_date: '2026-11-09'
provider_name: Green Dot
provider_slug: green-dot
slug: green-dot-eligibility
source_date: '2026-11-09'
source_filename: green-dot-eligibility.yml
source_heading: Eligibility
source_page: https://developer.greendot.com/embedded-finance/docs/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Green Dot\naid: green-dot\nurl: https://developer.greendot.com/embedded-finance/docs/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: an individual end user (“You” “Your”) of the Green Dot developer portal website\nrestricted_uses:\n- summary: Blocking for suspected violations\n  text: If Green Dot suspects that You have violated the requirements of this Section, Green Dot may block Your\n    access to the Site without advanced notice\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/green-dot/eligibility/green-dot-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Green Dot's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Banking as a Service
- Embedded Finance
- Prepaid Cards
- Banking
- Payments
- Money Movement
- United States
---
