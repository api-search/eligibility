---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are an individual, you must be at least 18 years old, and legally able to carry out your business in your jurisdiction.
    type: individual
  - text: If you are entering into this Agreement on behalf of a company or other legal entity, you represent that you have the authority to bind such entity to the terms of this Agreement
    type: business
  minimum_age:
    text: If you are an individual, you must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: unlawful or abusive content
    text: You agree not to upload, transmit or otherwise make available in connection with the Services any User Content that is unlawful
  - summary: personal or household use
    text: You confirm that you will use the Services solely for the purposes of carrying on a business activity and not for any personal, household or family purpose.
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
name: Bokun
provenance_date: '2026-11-09'
provider_name: Bokun
provider_slug: bokun
slug: bokun-eligibility
source_date: '2026-11-09'
source_filename: bokun-eligibility.yml
source_heading: Eligibility
source_page: https://www.bokun.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bokun\naid: bokun\nurl: https://www.bokun.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are an individual, you must be at least 18 years old, and legally able to carry out your business\n    in your jurisdiction.\n- type: business\n  text: If you are entering into this Agreement on behalf of a company or other legal entity, you represent that\n    you have the authority to bind such entity to the terms of this Agreement\nrestricted_uses:\n- summary: unlawful or abusive content\n  text: You agree not to upload, transmit\
  \ or otherwise make available in connection with the Services any User Content\n    that is unlawful\n- summary: personal or household use\n  text: You confirm that you will use the Services solely for the purposes of carrying on a business activity and\n    not for any personal, household or family purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are an individual, you must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/bokun/eligibility/bokun-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Bokun's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Travel
- Software-as-a-Service
- Booking
- Tour
---
