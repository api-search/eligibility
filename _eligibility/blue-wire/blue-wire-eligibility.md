---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services and the Site are offered and operated by us from our offices within the United States and we make no representation that the Services and/or Site are appropriate or available for use in other countries
  entity_types:
  - text: solely for your lawful internal business purposes
    type: business
  minimum_age:
    text: YOU MUST BE AT LEAST 18 YEARS OF AGE TO ACCESS AND VIEW THE SITE, THE SERVICES OFFERED, AND ANY CONTENT INCLUDED THEREON.
    value: '18'
  restricted_uses:
  - summary: Illegal gambling and cash-based gaming
    text: the Services and use hereof are not intended to be used in connection with any illegal or unlawful gambling, or any type of cash-based gaming activities
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: The Company may, in its sole discretion, elect to reject your application for enrollment for any reason, or for no reason at all.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Blue Wire
provenance_date: '2026-11-09'
provider_name: Blue Wire
provider_slug: blue-wire
slug: blue-wire-eligibility
source_date: '2026-11-09'
source_filename: blue-wire-eligibility.yml
source_heading: Eligibility
source_page: https://bluewirepods.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Blue Wire\naid: blue-wire\nurl: https://bluewirepods.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services and the Site are offered and operated by us from our offices within the United States and we\n    make no representation that the Services and/or Site are appropriate or available for use in other countries\nentity_types:\n- type: business\n  text: solely for your lawful internal business purposes\nrestricted_uses:\n- summary: Illegal gambling and cash-based gaming\n  text: the Services and use hereof are not intended to be\
  \ used in connection with any illegal or unlawful gambling,\n    or any type of cash-based gaming activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: The Company may, in its sole discretion, elect to reject your application for enrollment for any reason,\n    or for no reason at all.\nminimum_age:\n  value: '18'\n  text: YOU MUST BE AT LEAST 18 YEARS OF AGE TO ACCESS AND VIEW THE SITE, THE SERVICES OFFERED, AND ANY CONTENT\n    INCLUDED THEREON.\n"
source_yaml_url: https://artifacts.apis.io/blue-wire/eligibility/blue-wire-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Blue Wire's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Podcasts
- Media
- Sports
- Advertising
- Monetization
- Content Creators
---
