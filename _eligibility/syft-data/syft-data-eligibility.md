---
api_specs:
- filename: syft-data-export-api-openapi.yml
  format: yaml
  label: Syft Data Export API
  slug: syft-data-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/syft-data/openapi/syft-data-export-api-openapi.yml
- filename: syft-data-lookup-api-openapi.yml
  format: yaml
  label: Syft Data Lookup API
  slug: syft-data-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/syft-data/openapi/syft-data-lookup-api-openapi.yml
- filename: syft-data-events-api-openapi.yml
  format: yaml
  label: Syft Data Event Collection API
  slug: syft-data-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/syft-data/openapi/syft-data-events-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accessing or using the Product on behalf of your company, you represent that you are authorized to accept this Agreement on behalf of your company.
    type: business
  - text: This Agreement is between Syft Data, Inc. and the company or person accessing or using the Product.
    type: individual
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
name: Syft Data
provenance_date: '2026-11-10'
provider_name: Syft Data
provider_slug: syft-data
slug: syft-data-eligibility
source_date: '2026-11-10'
source_filename: syft-data-eligibility.yml
source_heading: Eligibility
source_page: https://www.syftdata.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Syft Data\naid: syft-data\nurl: https://www.syftdata.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accessing or using the Product on behalf of your company, you represent that you are authorized\n    to accept this Agreement on behalf of your company.\n- type: individual\n  text: This Agreement is between Syft Data, Inc. and the company or person accessing or using the Product.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n \
  \ text: null\n"
source_yaml_url: https://artifacts.apis.io/syft-data/eligibility/syft-data-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Syft Data's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Lead Intelligence
- Intent Data
- Website Visitor Identification
- Sales Intelligence
- Go-To-Market
- Analytics
- MCP
---
