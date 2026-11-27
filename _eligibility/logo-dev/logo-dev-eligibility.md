---
api_specs:
- filename: logo-dev-account-api-openapi.yml
  format: yaml
  label: Logo.dev Account API
  slug: logo-dev-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logo-dev/openapi/logo-dev-account-api-openapi.yml
- filename: logo-dev-brands-api-openapi.yml
  format: yaml
  label: Logo.dev Brands API
  slug: logo-dev-brands-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logo-dev/openapi/logo-dev-brands-api-openapi.yml
- filename: logo-dev-flags-api-openapi.yml
  format: yaml
  label: Logo.dev Flags API
  slug: logo-dev-flags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logo-dev/openapi/logo-dev-flags-api-openapi.yml
- filename: logo-dev-logo-cdn-api-openapi.yml
  format: yaml
  label: Logo.dev Logo CDN API
  slug: logo-dev-logo-cdn-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logo-dev/openapi/logo-dev-logo-cdn-api-openapi.yml
- filename: logo-dev-logos-api-openapi.yml
  format: yaml
  label: Logo.dev Logos API
  slug: logo-dev-logos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logo-dev/openapi/logo-dev-logos-api-openapi.yml
- filename: logo-dev-search-api-openapi.yml
  format: yaml
  label: Logo.dev Search API
  slug: logo-dev-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logo-dev/openapi/logo-dev-search-api-openapi.yml
- filename: logo-dev-subscriptions-api-openapi.yml
  format: yaml
  label: Logo.dev Subscriptions API
  slug: logo-dev-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logo-dev/openapi/logo-dev-subscriptions-api-openapi.yml
- filename: logo-dev-transaction-enrichment-api-api-openapi.yml
  format: yaml
  label: Logo.dev Transaction Enrichment API
  slug: logo-dev-transaction-enrichment-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logo-dev/openapi/logo-dev-transaction-enrichment-api-api-openapi.yml
- filename: logo-dev-webhook-endpoints-api-openapi.yml
  format: yaml
  label: Logo.dev Webhook endpoints API
  slug: logo-dev-webhook-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logo-dev/openapi/logo-dev-webhook-endpoints-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: whether personally or on behalf of an entity
    type: individual
  - text: If you are subscribing for the use of the Site on behalf of a legal entity, you represent and warrant that you are duly authorized to do so.
    type: business
  minimum_age:
    text: you are not a minor in the jurisdiction in which you reside
    value: null
  restricted_uses:
  - summary: Illegal purposes
    text: Company does not intend and expressly prohibits use of any of its APIs for any illegal purposes.
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
name: Logo.dev
provenance_date: '2026-11-09'
provider_name: Logo.dev
provider_slug: logo-dev
slug: logo-dev-eligibility
source_date: '2026-11-09'
source_filename: logo-dev-eligibility.yml
source_heading: Eligibility
source_page: https://www.logo.dev/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Logo.dev\naid: logo-dev\nurl: https://www.logo.dev/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: whether personally or on behalf of an entity\n- type: business\n  text: If you are subscribing for the use of the Site on behalf of a legal entity, you represent and warrant that\n    you are duly authorized to do so.\nrestricted_uses:\n- summary: Illegal purposes\n  text: Company does not intend and expressly prohibits use of any of its APIs for any illegal purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: you are not a minor in the jurisdiction in which you reside\n"
source_yaml_url: https://artifacts.apis.io/logo-dev/eligibility/logo-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Logo.dev's own page on 2026-11-09.
synthetic: false
tags:
- Logo
- Branding
- CDN
- Free Tier
---
