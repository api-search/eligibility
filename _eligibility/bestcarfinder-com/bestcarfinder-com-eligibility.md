---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: provided you are not barred from receiving the Services under the laws of the United States or other applicable jurisdictions
  entity_types:
  - text: The Services are intended only for individuals who are at least 18 years of age.
    type: individual
  - text: If you are accepting these Terms or using the Services on behalf of a company, organization, government, legal entity, or dealership, you represent and warrant that you have the authority to bind that entity to these Terms
    type: business
  minimum_age:
    text: The Services are intended only for individuals who are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Under-18 users barred
    text: No person under 18 may create an account, register for the Services, post a listing, submit a Car Wanted request, or send any personal information to us.
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
name: Best Car Finder
provenance_date: '2026-11-09'
provider_name: Best Car Finder
provider_slug: bestcarfinder-com
slug: bestcarfinder-com-eligibility
source_date: '2026-11-09'
source_filename: bestcarfinder-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.bestcarfinder.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Best Car Finder\naid: bestcarfinder-com\nurl: https://www.bestcarfinder.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: provided you are not barred from receiving the Services under the laws of the United States or other applicable\n    jurisdictions\nentity_types:\n- type: individual\n  text: The Services are intended only for individuals who are at least 18 years of age.\n- type: business\n  text: If you are accepting these Terms or using the Services on behalf of a company, organization, government,\n    legal entity, or dealership, you represent and warrant that\
  \ you have the authority to bind that entity to these\n    Terms\nrestricted_uses:\n- summary: Under-18 users barred\n  text: No person under 18 may create an account, register for the Services, post a listing, submit a Car Wanted\n    request, or send any personal information to us.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are intended only for individuals who are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/bestcarfinder-com/eligibility/bestcarfinder-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Best Car Finder's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Cars
- Used Vehicles
- Automotive
---
