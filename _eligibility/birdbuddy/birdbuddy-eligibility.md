---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Some features, benefits, capabilities and benefits may not be available in all countries. EEA-based consumers receive withdrawal and legal guarantee rights.
  entity_types:
  - text: The Premium Subscription Service is only available to end consumers aged 18 years or older.
    type: individual
  - text: If You are placing an Order for a legal entity, You represent and warrant that You have acquired consent from the statutory representative for placement of such Order.
    type: business
  minimum_age:
    text: By placing an Order through Website, You warrant that You are not a minor, that You are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: No resale or commercial use of subscription
    text: Premium Subscription users are not permitted to purchase the subscription and use its features for resale, rental, or other commercial purposes which includes sharing any benefits or capabilities with third parties.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may also require additional verifications or information before accepting any Order.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BirdBuddy
provenance_date: '2026-11-09'
provider_name: BirdBuddy
provider_slug: birdbuddy
slug: birdbuddy-eligibility
source_date: '2026-11-09'
source_filename: birdbuddy-eligibility.yml
source_heading: Eligibility
source_page: https://mybirdbuddy.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BirdBuddy\naid: birdbuddy\nurl: https://mybirdbuddy.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Some features, benefits, capabilities and benefits may not be available in all countries. EEA-based consumers\n    receive withdrawal and legal guarantee rights.\nentity_types:\n- type: individual\n  text: The Premium Subscription Service is only available to end consumers aged 18 years or older.\n- type: business\n  text: If You are placing an Order for a legal entity, You represent and warrant that You have acquired consent\n    from the statutory representative\
  \ for placement of such Order.\nrestricted_uses:\n- summary: No resale or commercial use of subscription\n  text: Premium Subscription users are not permitted to purchase the subscription and use its features for resale,\n    rental, or other commercial purposes which includes sharing any benefits or capabilities with third parties.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may also require additional verifications or information before accepting any Order.\nminimum_age:\n  value: '18'\n  text: By placing an Order through Website, You warrant that You are not a minor, that You are at least 18 years\n    of age\n"
source_yaml_url: https://artifacts.apis.io/birdbuddy/eligibility/birdbuddy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from BirdBuddy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Consumer Hardware
- Smart Home
- IoT
- Birding
- Computer Vision
- Mobile App
- GraphQL
---
