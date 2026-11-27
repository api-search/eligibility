---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: must only access, market, sell, ticket or distribute Virgin Australia Domestic and International Short-haul Product or Virgin Australia International Product within your PCC’s country of domicile unless authorised by Virgin Australia
  entity_types:
  - text: Agent means a registered travel agent making bookings for Guests with an Airline.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sales limited to PCC country of domicile
    text: must only access, market, sell, ticket or distribute Virgin Australia Domestic and International Short-haul Product or Virgin Australia International Product within your PCC’s country of domicile unless authorised by Virgin Australia
  - summary: No agency credit cards for payment
    text: Virgin Australia does not consent to the use of any credit card issued in the name of the Agent
  - source: https://www.virginaustralia.com/au/en/about-us/policies/legal/terms-of-use/chatgpt-app/
    summary: Personal and lawful purposes only
    text: use the App for personal and lawful purposes
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
name: Virgin Australia
provenance_date: '2026-11-10'
provider_name: Virgin Australia
provider_slug: virgin-australia
slug: virgin-australia-eligibility
source_date: '2026-11-10'
source_filename: virgin-australia-eligibility.yml
source_heading: Eligibility
source_page: https://www.virginaustralia.com/au/en/travel-info/flying-with-us/agency-hub/travel-agent-main-agreement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Virgin Australia\naid: virgin-australia\nurl: https://www.virginaustralia.com/au/en/travel-info/flying-with-us/agency-hub/travel-agent-main-agreement/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\n  sources:\n  - https://www.virginaustralia.com/au/en/about-us/policies/legal/terms-of-use/\n  - https://www.virginaustralia.com/au/en/about-us/policies/legal/terms-of-use/chatgpt-app/\n  - https://www.virginaustralia.com/au/en/travel-info/flying-with-us/agency-hub/travel-agent-main-agreement/\ncountries:\n  served: []\n  excluded: []\n  text: must only access, market, sell, ticket or distribute Virgin Australia Domestic\
  \ and International Short-haul\n    Product or Virgin Australia International Product within your PCC’s country of domicile unless authorised by\n    Virgin Australia\nentity_types:\n- type: business\n  text: Agent means a registered travel agent making bookings for Guests with an Airline.\nrestricted_uses:\n- summary: Sales limited to PCC country of domicile\n  text: must only access, market, sell, ticket or distribute Virgin Australia Domestic and International Short-haul\n    Product or Virgin Australia International Product within your PCC’s country of domicile unless authorised by\n    Virgin Australia\n- summary: No agency credit cards for payment\n  text: Virgin Australia does not consent to the use of any credit card issued in the name of the Agent\n- summary: Personal and lawful purposes only\n  text: use the App for personal and lawful purposes\n  source: https://www.virginaustralia.com/au/en/about-us/policies/legal/terms-of-use/chatgpt-app/\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/virgin-australia/eligibility/virgin-australia-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from Virgin Australia's own page on 2026-11-10.
synthetic: false
tags:
- Travel
- Australia
- Aviation
- Airlines
- Distribution
- GDS
- NDC
- Booking
- Loyalty
- Corporate Travel
---
