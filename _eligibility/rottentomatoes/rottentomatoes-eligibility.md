---
api_specs:
- filename: rottentomatoes-detailed-info-api-openapi.yml
  format: yaml
  label: Rotten Tomatoes Detailed Info API
  slug: rottentomatoes-detailed-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rottentomatoes/openapi/rottentomatoes-detailed-info-api-openapi.yml
- filename: rottentomatoes-dvd-lists-api-openapi.yml
  format: yaml
  label: Rotten Tomatoes DVD Lists API
  slug: rottentomatoes-dvd-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rottentomatoes/openapi/rottentomatoes-dvd-lists-api-openapi.yml
- filename: rottentomatoes-movie-lists-api-openapi.yml
  format: yaml
  label: Rotten Tomatoes Movie Lists API
  slug: rottentomatoes-movie-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rottentomatoes/openapi/rottentomatoes-movie-lists-api-openapi.yml
- filename: rottentomatoes-search-api-openapi.yml
  format: yaml
  label: Rotten Tomatoes Search API
  slug: rottentomatoes-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rottentomatoes/openapi/rottentomatoes-search-api-openapi.yml
- filename: rottentomatoes-top-level-lists-api-openapi.yml
  format: yaml
  label: Rotten Tomatoes Top Level Lists API
  slug: rottentomatoes-top-level-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rottentomatoes/openapi/rottentomatoes-top-level-lists-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served:
    - US
    text: The Services are for users who are 18 years of age or older and reside in the United States or (subject to availability) those outside the United States who, to the maximum extent permissible under applicable law, consent to use the Services in accordance with U.S. laws and these Terms. By accessing or otherwise using the Services, you represent and warrant that (i) you are not located in a country that is subject to a U.S. government embargo (e.g., Crimea, Cuba, Iran, North Korea or Syria)
  entity_types:
  - text: Our Site and other Services are for your personal and non-commercial use only.
    type: individual
  minimum_age:
    text: The Services are for users who are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Commercial use
    text: You have no right to use or otherwise access our Services for commercial use.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You agree that we may take steps to verify the information you provide.
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Rotten Tomatoes
provenance_date: '2026-11-10'
provider_name: Rotten Tomatoes
provider_slug: rottentomatoes
slug: rottentomatoes-eligibility
source_date: '2026-11-10'
source_filename: rottentomatoes-eligibility.yml
source_heading: Eligibility
source_page: https://www.rottentomatoes.com/policies/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rotten Tomatoes\naid: rottentomatoes\nurl: https://www.rottentomatoes.com/policies/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: The Services are for users who are 18 years of age or older and reside in the United States or (subject\n    to availability) those outside the United States who, to the maximum extent permissible under applicable law,\n    consent to use the Services in accordance with U.S. laws and these Terms. By accessing or otherwise using the\n    Services, you represent and warrant that (i) you are\
  \ not located in a country that is subject to a U.S. government\n    embargo (e.g., Crimea, Cuba, Iran, North Korea or Syria)\nentity_types:\n- type: individual\n  text: Our Site and other Services are for your personal and non-commercial use only.\nrestricted_uses:\n- summary: Commercial use\n  text: You have no right to use or otherwise access our Services for commercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You agree that we may take steps to verify the information you provide.\nminimum_age:\n  value: '18'\n  text: The Services are for users who are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/rottentomatoes/eligibility/rottentomatoes-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Rotten Tomatoes's own page on 2026-11-10.
synthetic: false
tags:
- Movies
- Television
- Reviews
- Ratings
- Tomatometer
- Audience Score
- Entertainment
- Media
---
