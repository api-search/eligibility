---
api_specs:
- filename: goatcounter-exports-api-openapi.yml
  format: yaml
  label: GoatCounter Exports API
  slug: goatcounter-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goatcounter/openapi/goatcounter-exports-api-openapi.yml
- filename: goatcounter-pageviews-api-openapi.yml
  format: yaml
  label: GoatCounter Pageviews API
  slug: goatcounter-pageviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goatcounter/openapi/goatcounter-pageviews-api-openapi.yml
- filename: goatcounter-paths-api-openapi.yml
  format: yaml
  label: GoatCounter Paths API
  slug: goatcounter-paths-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goatcounter/openapi/goatcounter-paths-api-openapi.yml
- filename: goatcounter-sites-api-openapi.yml
  format: yaml
  label: GoatCounter Sites API
  slug: goatcounter-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goatcounter/openapi/goatcounter-sites-api-openapi.yml
- filename: goatcounter-statistics-api-openapi.yml
  format: yaml
  label: GoatCounter Statistics API
  slug: goatcounter-statistics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goatcounter/openapi/goatcounter-statistics-api-openapi.yml
- filename: goatcounter-users-api-openapi.yml
  format: yaml
  label: GoatCounter Users API
  slug: goatcounter-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goatcounter/openapi/goatcounter-users-api-openapi.yml
- filename: goatcounter-count-api-openapi.yml
  format: yaml
  label: GoatCounter Count API
  slug: goatcounter-count-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goatcounter/openapi/goatcounter-count-api-openapi.yml
- filename: goatcounter-export-api-openapi.yml
  format: yaml
  label: GoatCounter Export API
  slug: goatcounter-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goatcounter/openapi/goatcounter-export-api-openapi.yml
- filename: goatcounter-stats-api-openapi.yml
  format: yaml
  label: GoatCounter Stats API
  slug: goatcounter-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goatcounter/openapi/goatcounter-stats-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The “user”, “you”, and “your” refers to any individual or organization which accesses our services.
    type: individual
  minimum_age:
    text: Accounts are only available to users who are 13 years of age or older, or the minimum age for accessing internet services in their country, whichever is older.
    value: '13'
  restricted_uses:
  - summary: High-volume pageviews
    text: but sending millions of pageviews/day isn’t.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We require an email address to register an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: GoatCounter
provenance_date: '2026-11-09'
provider_name: GoatCounter
provider_slug: goatcounter
slug: goatcounter-eligibility
source_date: '2026-11-09'
source_filename: goatcounter-eligibility.yml
source_heading: Eligibility
source_page: https://www.goatcounter.com/help/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GoatCounter\naid: goatcounter\nurl: https://www.goatcounter.com/help/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The “user”, “you”, and “your” refers to any individual or organization which accesses our services.\nrestricted_uses:\n- summary: High-volume pageviews\n  text: but sending millions of pageviews/day isn’t.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We require an email address to register an account.\nminimum_age:\n  value: '13'\n  text: Accounts are only available to users who\
  \ are 13 years of age or older, or the minimum age for accessing\n    internet services in their country, whichever is older.\n"
source_yaml_url: https://artifacts.apis.io/goatcounter/eligibility/goatcounter-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from GoatCounter's own page on 2026-11-09.
synthetic: false
tags:
- Analytics
- Page Views
- Privacy
- Statistics
- Web Analytics
- Open Source
- Self-Hosted
- Event
- Data Export
- Developer Tools
---
