---
api_specs:
- filename: realtor-ca-destination-api-openapi.yml
  format: yaml
  label: REALTOR.ca Destination API
  slug: realtor-ca-destination-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/realtor-ca/openapi/realtor-ca-destination-api-openapi.yml
- filename: realtor-ca-lead-api-openapi.yml
  format: yaml
  label: REALTOR.ca Lead API
  slug: realtor-ca-lead-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/realtor-ca/openapi/realtor-ca-lead-api-openapi.yml
- filename: realtor-ca-member-api-openapi.yml
  format: yaml
  label: REALTOR.ca Member API
  slug: realtor-ca-member-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/realtor-ca/openapi/realtor-ca-member-api-openapi.yml
- filename: realtor-ca-office-api-openapi.yml
  format: yaml
  label: REALTOR.ca Office API
  slug: realtor-ca-office-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/realtor-ca/openapi/realtor-ca-office-api-openapi.yml
- filename: realtor-ca-openhouse-api-openapi.yml
  format: yaml
  label: REALTOR.ca Open House API
  slug: realtor-ca-openhouse-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/realtor-ca/openapi/realtor-ca-openhouse-api-openapi.yml
- filename: realtor-ca-property-api-openapi.yml
  format: yaml
  label: REALTOR.ca Property API
  slug: realtor-ca-property-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/realtor-ca/openapi/realtor-ca-property-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: REALTOR.ca DDF® is a managed service for REALTORS® and broker owners who are looking to share listings with multiple third-party websites
    type: other
  minimum_age:
    text: null
    value: null
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
name: REALTOR.ca
provenance_date: '2026-11-10'
provider_name: REALTOR.ca
provider_slug: realtor-ca
slug: realtor-ca-eligibility
source_date: '2026-11-10'
source_filename: realtor-ca-eligibility.yml
source_heading: Eligibility
source_page: https://www.crea.ca/technology/realtor-ca-for-realtors/realtor-ca-tools/realtor-ca-ddf/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: REALTOR.ca\naid: realtor-ca\nurl: https://www.crea.ca/technology/realtor-ca-for-realtors/realtor-ca-tools/realtor-ca-ddf/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: REALTOR.ca DDF® is a managed service for REALTORS® and broker owners who are looking to share listings with\n    multiple third-party websites\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/realtor-ca/eligibility/realtor-ca-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from REALTOR.ca's own page on 2026-11-10.
synthetic: false
tags:
- Real Estate
- Canada
- Property Listings
- MLS
- RESO
- IDX
- Listing Syndication
- PropTech
- OData
- Rentals
---
