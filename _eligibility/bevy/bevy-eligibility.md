---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not subscribe to the Service as a Host on our “Starter” plan as described on https://www.bevy.com/b/pricing if you are a resident of the European Union or the United Kingdom.
  entity_types:
  - text: companies, businesses, individuals and organizations who use Bevy’s platform to organize and host their Events and who have purchased paid subscriptions
    type: business
  minimum_age:
    text: You may not use the Service if you are under the age of 16.
    value: '16'
  restricted_uses:
  - summary: Contract capacity
    text: Use our site, including its services and or tools if you are not able to form legally binding contracts
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
name: Bevy
provenance_date: '2026-11-09'
provider_name: Bevy
provider_slug: bevy
slug: bevy-eligibility
source_date: '2026-11-09'
source_filename: bevy-eligibility.yml
source_heading: Eligibility
source_page: https://bevy.com/b/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bevy\naid: bevy\nurl: https://bevy.com/b/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not subscribe to the Service as a Host on our “Starter” plan as described on https://www.bevy.com/b/pricing\n    if you are a resident of the European Union or the United Kingdom.\nentity_types:\n- type: business\n  text: companies, businesses, individuals and organizations who use Bevy’s platform to organize and host their\n    Events and who have purchased paid subscriptions\nrestricted_uses:\n- summary: Contract capacity\n  text: Use our site, including its services and\
  \ or tools if you are not able to form legally binding contracts\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You may not use the Service if you are under the age of 16.\n"
source_yaml_url: https://artifacts.apis.io/bevy/eligibility/bevy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Bevy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise
- Community
- Community Management
- Event
- Engagement
- Analytics
- Software-as-a-Service
---
