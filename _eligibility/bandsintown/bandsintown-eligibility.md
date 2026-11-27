---
api_specs:
- filename: bandsintown-artist-events-api-openapi.yml
  format: yaml
  label: Bandsintown artist events API
  slug: bandsintown-artist-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bandsintown/openapi/bandsintown-artist-events-api-openapi.yml
- filename: bandsintown-artist-information-api-openapi.yml
  format: yaml
  label: Bandsintown artist information API
  slug: bandsintown-artist-information-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bandsintown/openapi/bandsintown-artist-information-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Some countries may have more protective national consumer laws; no country list given.
  minimum_age:
    text: The Fan represents and warrants that he/she has reached the legal age of majority in his/her jurisdiction.
    value: age of majority
  restricted_uses:
  - summary: Minors
    text: The Platform and Services are prohibited for use by minors unauthorized to access and register to online services according to the laws of their country of residence.
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
name: Bandsintown
provenance_date: '2026-11-09'
provider_name: Bandsintown
provider_slug: bandsintown
slug: bandsintown-eligibility
source_date: '2026-11-09'
source_filename: bandsintown-eligibility.yml
source_heading: Eligibility
source_page: https://corp.bandsintown.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bandsintown\naid: bandsintown\nurl: https://corp.bandsintown.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Some countries may have more protective national consumer laws; no country list given.\nentity_types: []\nrestricted_uses:\n- summary: Minors\n  text: The Platform and Services are prohibited for use by minors unauthorized to access and register to online\n    services according to the laws of their country of residence.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: The Fan represents\
  \ and warrants that he/she has reached the legal age of majority in his/her jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/bandsintown/eligibility/bandsintown-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Bandsintown's own page on 2026-11-09.
synthetic: false
tags:
- Concerts
- Live Music
- Event
- Artists
- Venues
- Music Discovery
- tour dates
- Ticketing
- fan notifications
- Entertainment
---
