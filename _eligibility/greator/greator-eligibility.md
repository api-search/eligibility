---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If the customer is a consumer, he generally has the right to cancel the contract within 14 days without giving a reason.
    type: individual
  - text: The exclusive venue for all disputes arising out of or in connection with the contractual relationship, including these General Terms and Conditions, as well as those concerning validity, termination, and cessation, shall be Cologne if the customer is a business entity.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No commercial resale of tickets or programs
    text: The commercial resale of event tickets, online courses, or coaching training programs is prohibited.
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
name: Greator
provenance_date: '2026-11-09'
provider_name: Greator
provider_slug: greator
slug: greator-eligibility
source_date: '2026-11-09'
source_filename: greator-eligibility.yml
source_heading: Eligibility
source_page: https://greator.com/en/agb/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Greator\naid: greator\nurl: https://greator.com/en/agb/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If the customer is a consumer, he generally has the right to cancel the contract within 14 days without\n    giving a reason.\n- type: business\n  text: The exclusive venue for all disputes arising out of or in connection with the contractual relationship,\n    including these General Terms and Conditions, as well as those concerning validity, termination, and cessation,\n    shall be Cologne if the customer is a business entity.\n\
  restricted_uses:\n- summary: No commercial resale of tickets or programs\n  text: The commercial resale of event tickets, online courses, or coaching training programs is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/greator/eligibility/greator-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Greator's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Personal Development
- Coaching
- E-Learning
- Wellness
- Event
- Germany
---
