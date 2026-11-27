---
api_specs:
- filename: ezoic-access-api-openapi.yml
  format: yaml
  label: ezoic Access API
  slug: ezoic-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ezoic/openapi/ezoic-access-api-openapi.yml
- filename: ezoic-products-api-openapi.yml
  format: yaml
  label: ezoic Products API
  slug: ezoic-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ezoic/openapi/ezoic-products-api-openapi.yml
- filename: ezoic-purchases-api-openapi.yml
  format: yaml
  label: ezoic Purchases API
  slug: ezoic-purchases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ezoic/openapi/ezoic-purchases-api-openapi.yml
- filename: ezoic-cdn-api-openapi.yml
  format: yaml
  label: ezoic CDN API
  slug: ezoic-cdn-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ezoic/openapi/ezoic-cdn-api-openapi.yml
- filename: ezoic-data-api-openapi.yml
  format: yaml
  label: ezoic Data API
  slug: ezoic-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ezoic/openapi/ezoic-data-api-openapi.yml
- filename: ezoic-filters-api-openapi.yml
  format: yaml
  label: ezoic Filters API
  slug: ezoic-filters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ezoic/openapi/ezoic-filters-api-openapi.yml
- filename: ezoic-reports-api-openapi.yml
  format: yaml
  label: ezoic Reports API
  slug: ezoic-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ezoic/openapi/ezoic-reports-api-openapi.yml
- filename: ezoic-segments-api-openapi.yml
  format: yaml
  label: ezoic Segments API
  slug: ezoic-segments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ezoic/openapi/ezoic-segments-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The owner of the Website and Services is based in the United States. We make no claims that the Website, Services or any related content is accessible or appropriate outside of the United States.
  entity_types:
  - text: if individually that you or your representative or agent are at least 18 years of age
    type: individual
  - text: if entering into the Terms of Service for an organization, that you have the legal authority to bind that organization
    type: business
  minimum_age:
    text: if individually that you or your representative or agent are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Competitive product
    text: For purposes of building or marketing a competitive product.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Your use of the Services is subject to your creation and our approval of an Ezoic account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ezoic
provenance_date: '2026-11-09'
provider_name: ezoic
provider_slug: ezoic
slug: ezoic-eligibility
source_date: '2026-11-09'
source_filename: ezoic-eligibility.yml
source_heading: Eligibility
source_page: https://www.ezoic.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ezoic\naid: ezoic\nurl: https://www.ezoic.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The owner of the Website and Services is based in the United States. We make no claims that the Website,\n    Services or any related content is accessible or appropriate outside of the United States.\nentity_types:\n- type: individual\n  text: if individually that you or your representative or agent are at least 18 years of age\n- type: business\n  text: if entering into the Terms of Service for an organization, that you have the legal authority to bind that\n \
  \   organization\nrestricted_uses:\n- summary: Competitive product\n  text: For purposes of building or marketing a competitive product.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Your use of the Services is subject to your creation and our approval of an Ezoic account\nminimum_age:\n  value: '18'\n  text: if individually that you or your representative or agent are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/ezoic/eligibility/ezoic-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from ezoic's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Advertising
- AdTech
- Publisher Monetization
- Analytics
- Reporting
- Subscription
- Paywalls
- Identity
- CDN
- Caching
- MCP
- OAuth
- Agents
- Authentication
---
