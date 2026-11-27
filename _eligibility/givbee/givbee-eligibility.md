---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if you are registering for the Services as an individual, that you are at least 18 years of age and have the legal capacity to enter into this Agreement
    type: individual
  - text: if you are registering for the Services as an entity or organization, that (a) you are duly authorized to do business in the country or countries where you operate
    type: business
  minimum_age:
    text: if you are registering for the Services as an individual, that you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Alcohol or adult content to minors
    text: alcoholic beverages or entertainment content or promotions targeted to people under 21 years of age may not be sent through the system.
  - summary: Pornographic or sexually explicit content
    text: content affiliated with pornographic or sexually explicit material or alcoholic beverages is prohibited.
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
name: GivBee
provenance_date: '2026-11-09'
provider_name: GivBee
provider_slug: givbee
slug: givbee-eligibility
source_date: '2026-11-09'
source_filename: givbee-eligibility.yml
source_heading: Eligibility
source_page: https://www.givbee.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GivBee\naid: givbee\nurl: https://www.givbee.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: if you are registering for the Services as an individual, that you are at least 18 years of age and have\n    the legal capacity to enter into this Agreement\n- type: business\n  text: if you are registering for the Services as an entity or organization, that (a) you are duly authorized to\n    do business in the country or countries where you operate\nrestricted_uses:\n- summary: Alcohol or adult content to minors\n \
  \ text: alcoholic beverages or entertainment content or promotions targeted to people under 21 years of age may\n    not be sent through the system.\n- summary: Pornographic or sexually explicit content\n  text: content affiliated with pornographic or sexually explicit material or alcoholic beverages is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: if you are registering for the Services as an individual, that you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/givbee/eligibility/givbee-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from GivBee's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Messaging
- SMS
- Non-Profit
- Small Business
---
