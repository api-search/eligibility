---
api_specs:
- filename: stat-api-com-dfs-api-openapi.yml
  format: yaml
  label: stat-api-com DFS API
  slug: stat-api-com-dfs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stat-api-com/openapi/stat-api-com-dfs-api-openapi.yml
- filename: stat-api-com-mlb-api-openapi.yml
  format: yaml
  label: stat-api-com MLB API
  slug: stat-api-com-mlb-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stat-api-com/openapi/stat-api-com-mlb-api-openapi.yml
- filename: stat-api-com-nba-api-openapi.yml
  format: yaml
  label: stat-api-com NBA API
  slug: stat-api-com-nba-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stat-api-com/openapi/stat-api-com-nba-api-openapi.yml
- filename: stat-api-com-nfl-api-openapi.yml
  format: yaml
  label: stat-api-com NFL API
  slug: stat-api-com-nfl-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stat-api-com/openapi/stat-api-com-nfl-api-openapi.yml
- filename: stat-api-com-nhl-api-openapi.yml
  format: yaml
  label: stat-api-com NHL API
  slug: stat-api-com-nhl-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stat-api-com/openapi/stat-api-com-nhl-api-openapi.yml
- filename: stat-api-com-pga-api-openapi.yml
  format: yaml
  label: stat-api-com PGA API
  slug: stat-api-com-pga-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stat-api-com/openapi/stat-api-com-pga-api-openapi.yml
- filename: stat-api-com-reference-api-openapi.yml
  format: yaml
  label: stat-api-com Reference API
  slug: stat-api-com-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stat-api-com/openapi/stat-api-com-reference-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You must not be barred from using the Service under any applicable law or sanctions list.
  entity_types:
  - text: You must be at least 18 years old and able to form a binding contract
    type: individual
  - text: If you use the Service on behalf of an organization, you represent that you are authorized to bind it to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Gambling operation
    text: use the Service to operate a sportsbook, betting exchange, or other gambling operation
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You register through a supported sign-in provider (currently Google).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: stat-api-com
provenance_date: '2026-11-10'
provider_name: stat-api-com
provider_slug: stat-api-com
slug: stat-api-com-eligibility
source_date: '2026-11-10'
source_filename: stat-api-com-eligibility.yml
source_heading: Eligibility
source_page: https://stat-api.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: stat-api-com\naid: stat-api-com\nurl: https://stat-api.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You must not be barred from using the Service under any applicable law or sanctions list.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to form a binding contract\n- type: business\n  text: If you use the Service on behalf of an organization, you represent that you are authorized to bind it to\n    these Terms.\nrestricted_uses:\n- summary: Gambling operation\n  text: use the Service to operate a sportsbook, betting exchange, or\
  \ other gambling operation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You register through a supported sign-in provider (currently Google).\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/stat-api-com/eligibility/stat-api-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from stat-api-com's own page on 2026-11-10.
synthetic: false
tags:
- Sports
- Data
- DFS
- Fantasy
---
