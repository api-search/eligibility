---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: Our site is directed to people residing in the United Kingdom only. We do not represent that our site is appropriate for use or available in other locations.
  entity_types:
  - text: you agree that you are a private individual at least 18 years old and are present in the United Kingdom at the time you use the Platform.
    type: individual
  - text: for your own personal private or (if you are a business) internal business use
    type: business
  minimum_age:
    text: you are a private individual at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Consumers limited to domestic use
    text: We only supply the Platform for your own individual domestic and private use. You agree not to use the Platform in the course of any business, or for any commercial, business or re-sale purpose.
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
name: Click Mechanic
provenance_date: '2026-11-09'
provider_name: Click Mechanic
provider_slug: click-mechanic
slug: click-mechanic-eligibility
source_date: '2026-11-09'
source_filename: click-mechanic-eligibility.yml
source_heading: Eligibility
source_page: https://www.clickmechanic.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Click Mechanic\naid: click-mechanic\nurl: https://www.clickmechanic.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: Our site is directed to people residing in the United Kingdom only. We do not represent that our site is\n    appropriate for use or available in other locations.\nentity_types:\n- type: individual\n  text: you agree that you are a private individual at least 18 years old and are present in the United Kingdom\n    at the time you use the Platform.\n- type: business\n  text: for your own personal private or (if you are a business) internal business use\n\
  restricted_uses:\n- summary: Consumers limited to domestic use\n  text: We only supply the Platform for your own individual domestic and private use. You agree not to use the Platform\n    in the course of any business, or for any commercial, business or re-sale purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are a private individual at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/click-mechanic/eligibility/click-mechanic-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Click Mechanic's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Automotive
- Car Repair
- Marketplace
- Mobile Mechanics
- MOT
- Servicing
- United Kingdom
- Booking Platform
---
