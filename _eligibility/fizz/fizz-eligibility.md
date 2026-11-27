---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are intended only for individuals who are at least 18 years old.
    type: individual
  - text: Where you enter into this Agreement on behalf of a company or other organization, you represent and warrant that you have authority to act on behalf of that entity and to bind that entity to this Agreement.
    type: business
  minimum_age:
    text: You represent and warrant that you are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Journalistic, investigative or unlawful purposes disclosure
    text: including without limitation, if you are using or will or intend to use the Services for any journalistic, investigative, or unlawful purpose.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: Some features of the Services, including access to college-specific communities, may require verification of college affiliation.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Fizz
provenance_date: '2026-11-09'
provider_name: Fizz
provider_slug: fizz
slug: fizz-eligibility
source_date: '2026-11-09'
source_filename: fizz-eligibility.yml
source_heading: Eligibility
source_page: https://fizz.social/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fizz\naid: fizz\nurl: https://fizz.social/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Services are intended only for individuals who are at least 18 years old.\n- type: business\n  text: Where you enter into this Agreement on behalf of a company or other organization, you represent and warrant\n    that you have authority to act on behalf of that entity and to bind that entity to this Agreement.\nrestricted_uses:\n- summary: Journalistic, investigative or unlawful purposes disclosure\n  text: including without limitation,\
  \ if you are using or will or intend to use the Services for any journalistic,\n    investigative, or unlawful purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: Some features of the Services, including access to college-specific communities, may require verification\n    of college affiliation.\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/fizz/eligibility/fizz-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Fizz's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Social
- Social Network
- Community
- Campus
- Higher Education
- Students
- Consumer
- Mobile
- Marketplace
- Gen Z
- College
- Advertising
---
