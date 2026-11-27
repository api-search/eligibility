---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You are prohibited from using the Services if you are (a) a resident of any U.S. embargoed countries or any country that has been designated by the U.S. Government as a “terrorist supporting” country
  entity_types:
  - text: You must be 21 years of age or older to become a Wander member and use the Services.
    type: individual
  - text: If you use the Services on behalf of a company or other entity then “you” includes you and that entity
    type: business
  minimum_age:
    text: You must be 21 years of age or older to become a Wander member and use the Services.
    value: '21'
  restricted_uses:
  - summary: Alcohol under 21
    text: Consume alcohol if you are under the age of 21 or furnish alcohol to anyone under the age of 21 in connection with your use of the Services.
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
name: Wander
provenance_date: '2026-11-10'
provider_name: Wander
provider_slug: wander
slug: wander-eligibility
source_date: '2026-11-10'
source_filename: wander-eligibility.yml
source_heading: Eligibility
source_page: https://www.wander.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wander\naid: wander\nurl: https://www.wander.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You are prohibited from using the Services if you are (a) a resident of any U.S. embargoed countries or\n    any country that has been designated by the U.S. Government as a “terrorist supporting” country\nentity_types:\n- type: individual\n  text: You must be 21 years of age or older to become a Wander member and use the Services.\n- type: business\n  text: If you use the Services on behalf of a company or other entity then “you” includes you and that entity\nrestricted_uses:\n\
  - summary: Alcohol under 21\n  text: Consume alcohol if you are under the age of 21 or furnish alcohol to anyone under the age of 21 in connection\n    with your use of the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '21'\n  text: You must be 21 years of age or older to become a Wander member and use the Services.\n"
source_yaml_url: https://artifacts.apis.io/wander/eligibility/wander-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Wander's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Travel
- Hospitality
- Vacation Rentals
- Smart Homes
- Concierge
- Artificial Intelligence
---
