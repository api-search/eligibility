---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This site is intended for U.S. residents only.
  entity_types:
  - text: If you are using or opening an account on the Site on behalf of a company, entity, or organization (a “Subscribing Organization”)
    type: business
  - text: You much be 18 years of age or older to use this Site or to purchase a Croissant membership.
    type: individual
  minimum_age:
    text: You much be 18 years of age or older to use this Site or to purchase a Croissant membership.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Members must provide accurate and sufficient profile information so partner spaces can verify their identity upon check-in.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Croissant
provenance_date: '2026-11-09'
provider_name: Croissant
provider_slug: croissant
slug: croissant-eligibility
source_date: '2026-11-09'
source_filename: croissant-eligibility.yml
source_heading: Eligibility
source_page: https://www.getcroissant.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Croissant\naid: croissant\nurl: https://www.getcroissant.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This site is intended for U.S. residents only.\nentity_types:\n- type: business\n  text: If you are using or opening an account on the Site on behalf of a company, entity, or organization (a “Subscribing\n    Organization”)\n- type: individual\n  text: You much be 18 years of age or older to use this Site or to purchase a Croissant membership.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Members must provide accurate\
  \ and sufficient profile information so partner spaces can verify their identity\n    upon check-in.\nminimum_age:\n  value: '18'\n  text: You much be 18 years of age or older to use this Site or to purchase a Croissant membership.\n"
source_yaml_url: https://artifacts.apis.io/croissant/eligibility/croissant-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 5 quoted statements, read from Croissant's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Co-Working
- Workspace Management
- Distributed Teams
- Real Estate
- Spend Management
- Booking
- Software-as-a-Service
---
