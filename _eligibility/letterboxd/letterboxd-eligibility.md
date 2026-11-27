---
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Letterboxd API
  slug: letterboxd-api
  spec_type: OpenAPI
  url: https://api-docs.letterboxd.com/
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: In order to use the Service, you must be at least 16 years of age.
    type: individual
  minimum_age:
    text: In order to use the Service, you must be at least 16 years of age.
    value: '16'
  restricted_uses:
  - summary: Sanctioned persons
    text: You represent, warrant, and covenant that you will not sign-up for or otherwise access or use the Service if you are the subject of US sanctions
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register for an account to use certain features of the Service.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Letterboxd
provenance_date: '2026-11-09'
provider_name: Letterboxd
provider_slug: letterboxd
slug: letterboxd-eligibility
source_date: '2026-11-09'
source_filename: letterboxd-eligibility.yml
source_heading: Eligibility
source_page: https://letterboxd.com/legal/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Letterboxd\naid: letterboxd\nurl: https://letterboxd.com/legal/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: In order to use the Service, you must be at least 16 years of age.\nrestricted_uses:\n- summary: Sanctioned persons\n  text: You represent, warrant, and covenant that you will not sign-up for or otherwise access or use the Service\n    if you are the subject of US sanctions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to register for an account\
  \ to use certain features of the Service.\nminimum_age:\n  value: '16'\n  text: In order to use the Service, you must be at least 16 years of age.\n"
source_yaml_url: https://artifacts.apis.io/letterboxd/eligibility/letterboxd-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Letterboxd's own page on 2026-11-09.
synthetic: false
tags:
- Film
- Movies
- Social
- Reviews
- Watchlist
- Ratings
- Diary
- Film Festival
- Entertainment
---
