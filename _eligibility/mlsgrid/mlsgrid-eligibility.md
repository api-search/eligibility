---
api_specs:
- filename: mlsgrid-lookup-api-openapi.yml
  format: yaml
  label: mlsgrid Lookup API
  slug: mlsgrid-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mlsgrid/openapi/mlsgrid-lookup-api-openapi.yml
- filename: mlsgrid-media-api-openapi.yml
  format: yaml
  label: mlsgrid Media API
  slug: mlsgrid-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mlsgrid/openapi/mlsgrid-media-api-openapi.yml
- filename: mlsgrid-member-api-openapi.yml
  format: yaml
  label: mlsgrid Member API
  slug: mlsgrid-member-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mlsgrid/openapi/mlsgrid-member-api-openapi.yml
- filename: mlsgrid-metadata-api-openapi.yml
  format: yaml
  label: mlsgrid Metadata API
  slug: mlsgrid-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mlsgrid/openapi/mlsgrid-metadata-api-openapi.yml
- filename: mlsgrid-office-api-openapi.yml
  format: yaml
  label: mlsgrid Office API
  slug: mlsgrid-office-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mlsgrid/openapi/mlsgrid-office-api-openapi.yml
- filename: mlsgrid-openhouse-api-openapi.yml
  format: yaml
  label: mlsgrid OpenHouse API
  slug: mlsgrid-openhouse-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mlsgrid/openapi/mlsgrid-openhouse-api-openapi.yml
- filename: mlsgrid-property-api-openapi.yml
  format: yaml
  label: mlsgrid Property API
  slug: mlsgrid-property-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mlsgrid/openapi/mlsgrid-property-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Unless otherwise specified, the Sites and the Content are intended to promote MLS GRID’s products and services available in the United States.
  minimum_age:
    text: MLS GRID only extends services to adults.
    value: adults
  restricted_uses:
  - summary: Spam
    text: MLS GRID prohibits the use of MLS GRID products in any manner associated with the transmission, distribution, or delivery of any unsolicited bulk or unsolicited commercial email (“Spam”).
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
name: Mlsgrid
provenance_date: '2026-11-10'
provider_name: Mlsgrid
provider_slug: mlsgrid
slug: mlsgrid-eligibility
source_date: '2026-11-10'
source_filename: mlsgrid-eligibility.yml
source_heading: Eligibility
source_page: https://app.mlsgrid.com/termsofuse
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mlsgrid\naid: mlsgrid\nurl: https://app.mlsgrid.com/termsofuse\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Unless otherwise specified, the Sites and the Content are intended to promote MLS GRID’s products and services\n    available in the United States.\nentity_types: []\nrestricted_uses:\n- summary: Spam\n  text: MLS GRID prohibits the use of MLS GRID products in any manner associated with the transmission, distribution,\n    or delivery of any unsolicited bulk or unsolicited commercial email (“Spam”).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: adults\n  text: MLS GRID only extends services to adults.\n"
source_yaml_url: https://artifacts.apis.io/mlsgrid/eligibility/mlsgrid-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Mlsgrid's own page on 2026-11-10.
synthetic: false
tags:
- Real Estate
- Property Listings
- MLS
- RESO
- Data Replication
- OData
- Housing
- Data Licensing
- IDX
- Property Data
---
