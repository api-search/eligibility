---
api_specs:
- filename: genius-account-api-openapi.yml
  format: yaml
  label: Genius Account API
  slug: genius-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/genius/openapi/genius-account-api-openapi.yml
- filename: genius-albums-api-openapi.yml
  format: yaml
  label: Genius Albums API
  slug: genius-albums-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/genius/openapi/genius-albums-api-openapi.yml
- filename: genius-annotations-api-openapi.yml
  format: yaml
  label: Genius Annotations API
  slug: genius-annotations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/genius/openapi/genius-annotations-api-openapi.yml
- filename: genius-artists-api-openapi.yml
  format: yaml
  label: Genius Artists API
  slug: genius-artists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/genius/openapi/genius-artists-api-openapi.yml
- filename: genius-referents-api-openapi.yml
  format: yaml
  label: Genius Referents API
  slug: genius-referents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/genius/openapi/genius-referents-api-openapi.yml
- filename: genius-search-api-openapi.yml
  format: yaml
  label: Genius Search API
  slug: genius-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/genius/openapi/genius-search-api-openapi.yml
- filename: genius-songs-api-openapi.yml
  format: yaml
  label: Genius Songs API
  slug: genius-songs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/genius/openapi/genius-songs-api-openapi.yml
- filename: genius-users-api-openapi.yml
  format: yaml
  label: Genius Users API
  slug: genius-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/genius/openapi/genius-users-api-openapi.yml
- filename: genius-web-pages-api-openapi.yml
  format: yaml
  label: Genius Web Pages API
  slug: genius-web-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/genius/openapi/genius-web-pages-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Unless otherwise explicitly stated, all materials found on the Service are solely directed to individuals, companies, or other entities located in the United States. You may not use the Service if you are a resident of a country embargoed by the United States
  entity_types:
  - text: This Service is intended solely for users who are 13 years of age or older.
    type: individual
  - text: If you open a Genius account on behalf of a company, organization, school, or other entity, then (i) "you" includes you and that entity
    type: business
  minimum_age:
    text: This Service is intended solely for users who are 13 years of age or older.
    value: '13'
  restricted_uses:
  - summary: Personal use; no commercial use without consent
    text: The Service is for your personal use and may not be used for direct commercial endeavors without the express written consent of Genius.
  - summary: Embargoed countries and blocked persons
    text: You may not use the Service if you are a resident of a country embargoed by the United States, or are a foreign person or entity blocked or denied by the United States government.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: If you choose to register for an account, you agree to provide and maintain true, accurate, current and complete information about yourself as prompted by our registration form.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Genius
provenance_date: '2026-11-09'
provider_name: Genius
provider_slug: genius
slug: genius-eligibility
source_date: '2026-11-09'
source_filename: genius-eligibility.yml
source_heading: Eligibility
source_page: https://genius.com/static/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Genius\naid: genius\nurl: https://genius.com/static/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Unless otherwise explicitly stated, all materials found on the Service are solely directed to individuals,\n    companies, or other entities located in the United States. You may not use the Service if you are a resident\n    of a country embargoed by the United States\nentity_types:\n- type: individual\n  text: This Service is intended solely for users who are 13 years of age or older.\n- type: business\n  text: If you open a Genius account on behalf of a company, organization,\
  \ school, or other entity, then (i) \"you\"\n    includes you and that entity\nrestricted_uses:\n- summary: Personal use; no commercial use without consent\n  text: The Service is for your personal use and may not be used for direct commercial endeavors without the express\n    written consent of Genius.\n- summary: Embargoed countries and blocked persons\n  text: You may not use the Service if you are a resident of a country embargoed by the United States, or are a\n    foreign person or entity blocked or denied by the United States government.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: If you choose to register for an account, you agree to provide and maintain true, accurate, current and\n    complete information about yourself as prompted by our registration form.\nminimum_age:\n  value: '13'\n  text: This Service is intended solely for users who are 13 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/genius/eligibility/genius-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Genius's own page on 2026-11-09.
synthetic: false
tags:
- Music
- Lyrics
- Annotation
- Crowdsourced
- Reference Data
- Public APIs
---
