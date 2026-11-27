---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We have the right to restrict the use of all or part of Firstory services and its software/website at any time for any person, region, or jurisdiction at our sole discretion.
  entity_types:
  - text: If you use Firstory services on behalf of a legal entity, you represent and warrant that you have full authority to sign contracts on behalf of the legal entity
    type: business
  minimum_age:
    text: You must be at least 20 years old or have reached the legal age of majority in your jurisdiction
    value: '20'
  restricted_uses:
  - summary: Sexual services and illegal goods
    text: You may not use Firstory to provide sexual services, buy and sell illegal goods or drugs (even if such drugs are legal in your area).
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
name: Firstory
provenance_date: '2026-11-09'
provider_name: Firstory
provider_slug: firstory
slug: firstory-eligibility
source_date: '2026-11-09'
source_filename: firstory-eligibility.yml
source_heading: Eligibility
source_page: https://firstory.me/en/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Firstory\naid: firstory\nurl: https://firstory.me/en/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We have the right to restrict the use of all or part of Firstory services and its software/website at any\n    time for any person, region, or jurisdiction at our sole discretion.\nentity_types:\n- type: business\n  text: If you use Firstory services on behalf of a legal entity, you represent and warrant that you have full authority\n    to sign contracts on behalf of the legal entity\nrestricted_uses:\n- summary: Sexual services and illegal goods\n  text: You may\
  \ not use Firstory to provide sexual services, buy and sell illegal goods or drugs (even if such drugs\n    are legal in your area).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '20'\n  text: You must be at least 20 years old or have reached the legal age of majority in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/firstory/eligibility/firstory-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Firstory's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Podcasts
- Podcast Hosting
- Media
- Audio
- Monetization
- Analytics
- Creator Tools
- Asia Pacific
---
