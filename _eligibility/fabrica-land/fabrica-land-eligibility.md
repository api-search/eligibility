---
api_specs:
- filename: fabrica-land-change-of-ownership-api-openapi.yml
  format: yaml
  label: fabrica-land Change Of Ownership API
  slug: fabrica-land-change-of-ownership-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fabrica-land/openapi/fabrica-land-change-of-ownership-api-openapi.yml
- filename: fabrica-land-document-api-openapi.yml
  format: yaml
  label: fabrica-land Document API
  slug: fabrica-land-document-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fabrica-land/openapi/fabrica-land-document-api-openapi.yml
- filename: fabrica-land-media-api-openapi.yml
  format: yaml
  label: fabrica-land Media API
  slug: fabrica-land-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fabrica-land/openapi/fabrica-land-media-api-openapi.yml
- filename: fabrica-land-metadata-api-openapi.yml
  format: yaml
  label: fabrica-land Metadata API
  slug: fabrica-land-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fabrica-land/openapi/fabrica-land-metadata-api-openapi.yml
- filename: fabrica-land-off-ramp-api-openapi.yml
  format: yaml
  label: fabrica-land Off Ramp API
  slug: fabrica-land-off-ramp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fabrica-land/openapi/fabrica-land-off-ramp-api-openapi.yml
- filename: fabrica-land-on-ramp-api-openapi.yml
  format: yaml
  label: fabrica-land On Ramp API
  slug: fabrica-land-on-ramp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fabrica-land/openapi/fabrica-land-on-ramp-api-openapi.yml
- filename: fabrica-land-pool-lending-api-openapi.yml
  format: yaml
  label: fabrica-land Pool Lending API
  slug: fabrica-land-pool-lending-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fabrica-land/openapi/fabrica-land-pool-lending-api-openapi.yml
- filename: fabrica-land-proof-of-ownership-api-openapi.yml
  format: yaml
  label: fabrica-land Proof Of Ownership API
  slug: fabrica-land-proof-of-ownership-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fabrica-land/openapi/fabrica-land-proof-of-ownership-api-openapi.yml
- filename: fabrica-land-regrid-api-openapi.yml
  format: yaml
  label: fabrica-land Regrid API
  slug: fabrica-land-regrid-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fabrica-land/openapi/fabrica-land-regrid-api-openapi.yml
- filename: fabrica-land-syndication-api-openapi.yml
  format: yaml
  label: fabrica-land Syndication API
  slug: fabrica-land-syndication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fabrica-land/openapi/fabrica-land-syndication-api-openapi.yml
- filename: fabrica-land-terrain-project-api-openapi.yml
  format: yaml
  label: fabrica-land Terrain Project API
  slug: fabrica-land-terrain-project-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fabrica-land/openapi/fabrica-land-terrain-project-api-openapi.yml
- filename: fabrica-land-token-api-openapi.yml
  format: yaml
  label: fabrica-land Token API
  slug: fabrica-land-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fabrica-land/openapi/fabrica-land-token-api-openapi.yml
- filename: fabrica-land-valuation-api-openapi.yml
  format: yaml
  label: fabrica-land Valuation API
  slug: fabrica-land-valuation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fabrica-land/openapi/fabrica-land-valuation-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is available only to individuals who are at least 18 years old (and at least the legal age in your jurisdiction).
    type: individual
  minimum_age:
    text: You represent and warrant that you are at least 18 years old and of legal age in your jurisdiction to form a binding contract
    value: '18'
  restricted_uses:
  - summary: Lending pool use subject to sanctions and prohibited-activity provisions
    text: Use of the lending interface is subject to the eligibility, sanctions, and prohibited-activity provisions of these Terms.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Fabrica may in its sole discretion refuse to offer use of the Site to any person or entity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: fabrica-land
provenance_date: '2026-11-09'
provider_name: fabrica-land
provider_slug: fabrica-land
slug: fabrica-land-eligibility
source_date: '2026-11-09'
source_filename: fabrica-land-eligibility.yml
source_heading: Eligibility
source_page: https://fabrica.land/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: fabrica-land\naid: fabrica-land\nurl: https://fabrica.land/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is available only to individuals who are at least 18 years old (and at least the legal age in your\n    jurisdiction).\nrestricted_uses:\n- summary: Lending pool use subject to sanctions and prohibited-activity provisions\n  text: Use of the lending interface is subject to the eligibility, sanctions, and prohibited-activity provisions\n    of these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: Fabrica may in its sole discretion refuse to offer use of the Site to any person or entity.\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are at least 18 years old and of legal age in your jurisdiction to form\n    a binding contract\n"
source_yaml_url: https://artifacts.apis.io/fabrica-land/eligibility/fabrica-land-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from fabrica-land's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- Blockchain
- Marketplace
- Fintech
---
