---
api_specs:
- filename: perchwell-listings-api-openapi.yml
  format: yaml
  label: Perchwell Listings API
  slug: perchwell-listings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/perchwell/openapi/perchwell-listings-api-openapi.yml
- filename: perchwell-media-api-openapi.yml
  format: yaml
  label: Perchwell Media API
  slug: perchwell-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/perchwell/openapi/perchwell-media-api-openapi.yml
- filename: perchwell-member-api-openapi.yml
  format: yaml
  label: Perchwell Member API
  slug: perchwell-member-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/perchwell/openapi/perchwell-member-api-openapi.yml
- filename: perchwell-metadata-api-openapi.yml
  format: yaml
  label: Perchwell Metadata API
  slug: perchwell-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/perchwell/openapi/perchwell-metadata-api-openapi.yml
- filename: perchwell-office-api-openapi.yml
  format: yaml
  label: Perchwell Office API
  slug: perchwell-office-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/perchwell/openapi/perchwell-office-api-openapi.yml
- filename: perchwell-openhouse-api-openapi.yml
  format: yaml
  label: Perchwell OpenHouse API
  slug: perchwell-openhouse-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/perchwell/openapi/perchwell-openhouse-api-openapi.yml
- filename: perchwell-property-api-openapi.yml
  format: yaml
  label: Perchwell Property API
  slug: perchwell-property-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/perchwell/openapi/perchwell-property-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are controlled and offered by Company from its facilities in the United States of America.
  entity_types:
  - text: (2) YOU ARE OVER 18 YEARS OF AGE, AND OF LEGAL AGE TO FORM A BINDING CONTRACT WITH PERCHWELL
    type: individual
  minimum_age:
    text: (2) YOU ARE OVER 18 YEARS OF AGE
    value: '18'
  restricted_uses:
  - summary: Authorized users only
    text: ACCESS TO THE SERVICES IS STRICTLY RESTRICTED, AND IS AVAILABLE ON AN AUTHORIZED BASIS ONLY
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
name: Perchwell
provenance_date: '2026-11-10'
provider_name: Perchwell
provider_slug: perchwell
slug: perchwell-eligibility
source_date: '2026-11-10'
source_filename: perchwell-eligibility.yml
source_heading: Eligibility
source_page: https://www.perchwell.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Perchwell\naid: perchwell\nurl: https://www.perchwell.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Services are controlled and offered by Company from its facilities in the United States of America.\nentity_types:\n- type: individual\n  text: (2) YOU ARE OVER 18 YEARS OF AGE, AND OF LEGAL AGE TO FORM A BINDING CONTRACT WITH PERCHWELL\nrestricted_uses:\n- summary: Authorized users only\n  text: ACCESS TO THE SERVICES IS STRICTLY RESTRICTED, AND IS AVAILABLE ON AN AUTHORIZED BASIS ONLY\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: (2) YOU ARE OVER 18 YEARS OF AGE\n"
source_yaml_url: https://artifacts.apis.io/perchwell/eligibility/perchwell-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Perchwell's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Real Estate
- MLS
- Listings
- Property Data
- RESO
- RETS
- OData
- Real Estate Data
---
