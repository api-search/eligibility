---
api_specs:
- filename: lune-accounts-api-openapi.yml
  format: yaml
  label: Lune Accounts API
  slug: lune-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lune/openapi/lune-accounts-api-openapi.yml
- filename: lune-analytics-api-openapi.yml
  format: yaml
  label: Lune Analytics API
  slug: lune-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lune/openapi/lune-analytics-api-openapi.yml
- filename: lune-bundle-portfolios-api-openapi.yml
  format: yaml
  label: Lune Bundle portfolios API
  slug: lune-bundle-portfolios-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lune/openapi/lune-bundle-portfolios-api-openapi.yml
- filename: lune-bundle-selections-api-openapi.yml
  format: yaml
  label: Lune Bundle selections API
  slug: lune-bundle-selections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lune/openapi/lune-bundle-selections-api-openapi.yml
- filename: lune-bundles-api-openapi.yml
  format: yaml
  label: Lune Bundles API
  slug: lune-bundles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lune/openapi/lune-bundles-api-openapi.yml
- filename: lune-client-accounts-api-openapi.yml
  format: yaml
  label: Lune Client accounts API
  slug: lune-client-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lune/openapi/lune-client-accounts-api-openapi.yml
- filename: lune-emission-estimates-api-openapi.yml
  format: yaml
  label: Lune Emission estimates API
  slug: lune-emission-estimates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lune/openapi/lune-emission-estimates-api-openapi.yml
- filename: lune-emission-factors-api-openapi.yml
  format: yaml
  label: Lune Emission factors API
  slug: lune-emission-factors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lune/openapi/lune-emission-factors-api-openapi.yml
- filename: lune-orders-api-openapi.yml
  format: yaml
  label: Lune Orders API
  slug: lune-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lune/openapi/lune-orders-api-openapi.yml
- filename: lune-payments-api-openapi.yml
  format: yaml
  label: Lune Payments API
  slug: lune-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lune/openapi/lune-payments-api-openapi.yml
- filename: lune-projects-api-openapi.yml
  format: yaml
  label: Lune Projects API
  slug: lune-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lune/openapi/lune-projects-api-openapi.yml
- filename: lune-shipments-api-openapi.yml
  format: yaml
  label: Lune Shipments API
  slug: lune-shipments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lune/openapi/lune-shipments-api-openapi.yml
- filename: lune-sustainability-page-api-openapi.yml
  format: yaml
  label: Lune Sustainability page API
  slug: lune-sustainability-page-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lune/openapi/lune-sustainability-page-api-openapi.yml
- filename: lune-webhook-request-api-openapi.yml
  format: yaml
  label: Lune Webhook request API
  slug: lune-webhook-request-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lune/openapi/lune-webhook-request-api-openapi.yml
- filename: lune-webhooks-api-openapi.yml
  format: yaml
  label: Lune Webhooks API
  slug: lune-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lune/openapi/lune-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you, the entity that has engaged Lune to provide the Platform and the Services
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or damaging material
    text: access, store, distribute or transmit any viruses, or any material during the course of its use of the Platform or the Services that is unlawful
  - summary: Competing products
    text: access all or any part of the Platform or the Services in order to build a product or service which competes with the Platform and/or the Services
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
name: Lune
provenance_date: '2026-11-10'
provider_name: Lune
provider_slug: lune
slug: lune-eligibility
source_date: '2026-11-10'
source_filename: lune-eligibility.yml
source_heading: Eligibility
source_page: https://lune.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lune\naid: lune\nurl: https://lune.co/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: you, the entity that has engaged Lune to provide the Platform and the Services\nrestricted_uses:\n- summary: Unlawful or damaging material\n  text: access, store, distribute or transmit any viruses, or any material during the course of its use of the Platform\n    or the Services that is unlawful\n- summary: Competing products\n  text: access all or any part of the Platform or the Services in order to build a product or service which competes\n \
  \   with the Platform and/or the Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/lune/eligibility/lune-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Lune's own page on 2026-11-10.
synthetic: false
tags:
- Logistics
- Emissions
- Carbon
- Supply Chain
- Sustainability
---
