---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The shipping country selector lists many countries, but the terms do not state which countries are served or excluded. Free shipping offers are only valid within the contiguous USA.
  entity_types:
  - text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state or province of residence
    type: individual
  minimum_age:
    text: You may not use or engage with the Platform if you are under thirteen (13) years of age.
    value: '13'
  restricted_uses:
  - summary: Prohibited uses list
    text: 'you are prohibited from using the site or its content: (a) for any unlawful purpose'
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
name: The Feed
provenance_date: '2026-11-10'
provider_name: The Feed
provider_slug: the-feed
slug: the-feed-eligibility
source_date: '2026-11-10'
source_filename: the-feed-eligibility.yml
source_heading: Eligibility
source_page: https://thefeed.com/page/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: The Feed\naid: the-feed\nurl: https://thefeed.com/page/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The shipping country selector lists many countries, but the terms do not state which countries are served\n    or excluded. Free shipping offers are only valid within the contiguous USA.\nentity_types:\n- type: individual\n  text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state\n    or province of residence\nrestricted_uses:\n- summary: Prohibited uses list\n  text: 'you are prohibited from using the site or its\
  \ content: (a) for any unlawful purpose'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You may not use or engage with the Platform if you are under thirteen (13) years of age.\n"
source_yaml_url: https://artifacts.apis.io/the-feed/eligibility/the-feed-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from The Feed's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Sports Nutrition
- E-Commerce
- Endurance Sports
- Hydration
- Supplements
- Subscription
---
