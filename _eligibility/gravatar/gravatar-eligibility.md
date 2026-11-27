---
api_specs:
- filename: gravatar-avatars-api-openapi.yml
  format: yaml
  label: Gravatar Avatars API
  slug: gravatar-avatars-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gravatar/openapi/gravatar-avatars-api-openapi.yml
- filename: gravatar-experimental-api-openapi.yml
  format: yaml
  label: Gravatar Experimental API
  slug: gravatar-experimental-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gravatar/openapi/gravatar-experimental-api-openapi.yml
- filename: gravatar-profiles-api-openapi.yml
  format: yaml
  label: Gravatar Profiles API
  slug: gravatar-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gravatar/openapi/gravatar-profiles-api-openapi.yml
- filename: gravatar-qr-code-api-openapi.yml
  format: yaml
  label: Gravatar Qr Code API
  slug: gravatar-qr-code-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gravatar/openapi/gravatar-qr-code-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Woo-related products and services are intended for commercial use and you acknowledge that your use is that of a representative of a business
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Embargoed countries for Ecommerce Services
    text: Ecommerce Services cannot be used in, from, by, or for the benefit of a country, organization, entity, or person embargoed or blocked by any government
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
name: Gravatar
provenance_date: '2026-11-09'
provider_name: Gravatar
provider_slug: gravatar
slug: gravatar-eligibility
source_date: '2026-11-09'
source_filename: gravatar-eligibility.yml
source_heading: Eligibility
source_page: https://automattic.com/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gravatar\naid: gravatar\nurl: https://automattic.com/tos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Woo-related products and services are intended for commercial use and you acknowledge that your use is that\n    of a representative of a business\nrestricted_uses:\n- summary: Embargoed countries for Ecommerce Services\n  text: Ecommerce Services cannot be used in, from, by, or for the benefit of a country, organization, entity, or\n    person embargoed or blocked by any government\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/gravatar/eligibility/gravatar-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Gravatar's own page on 2026-11-09.
synthetic: false
tags:
- Avatars
- Identity
- Profiles
- Social
- Image
- GraphQL
- REST
---
