---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Your travel agency, including affiliated agency locations under common control that are accredited by Airlines Reporting Corporation (“ARC”) or the International Air Transport Association (“IATA”)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Porter Data redistribution limits
    text: Agent’s Appointment is for purposes of the Agent marketing and selling Porter’s products and services directly to customers
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
name: Porter Airlines
provenance_date: '2026-11-10'
provider_name: Porter Airlines
provider_slug: porter-airlines
slug: porter-airlines-eligibility
source_date: '2026-11-10'
source_filename: porter-airlines-eligibility.yml
source_heading: Eligibility
source_page: https://www.flyporter.com/Content/Documents/TravelAgents/en/terms-and-conditions.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Porter Airlines\naid: porter-airlines\nurl: https://www.flyporter.com/Content/Documents/TravelAgents/en/terms-and-conditions.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Your travel agency, including affiliated agency locations under common control that are accredited by Airlines\n    Reporting Corporation (“ARC”) or the International Air Transport Association (“IATA”)\nrestricted_uses:\n- summary: Porter Data redistribution limits\n  text: Agent’s Appointment is for purposes of the Agent marketing and selling Porter’s products\
  \ and services directly\n    to customers\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/porter-airlines/eligibility/porter-airlines-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Porter Airlines's own page on 2026-11-10.
synthetic: false
tags:
- Travel
- Canada
- Aviation
- Airlines
- Flights
- Distribution
- GDS
- Booking
- Travel Agents
- Loyalty
---
