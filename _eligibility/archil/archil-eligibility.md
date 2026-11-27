---
api_specs:
- filename: archil-api-tokens-api-openapi.yml
  format: yaml
  label: Archil API Tokens API
  slug: archil-api-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archil/openapi/archil-api-tokens-api-openapi.yml
- filename: archil-disk-users-api-openapi.yml
  format: yaml
  label: Archil Disk Users API
  slug: archil-disk-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archil/openapi/archil-disk-users-api-openapi.yml
- filename: archil-disks-api-openapi.yml
  format: yaml
  label: Archil Disks API
  slug: archil-disks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archil/openapi/archil-disks-api-openapi.yml
- filename: archil-serverless-execution-api-openapi.yml
  format: yaml
  label: Archil Serverless Execution API
  slug: archil-serverless-execution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archil/openapi/archil-serverless-execution-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The company or person who accesses or uses the Product.
    type: individual
  - text: If you are accessing or using the Product on behalf of your company, you represent that you are authorized to accept this Agreement on behalf of your company.
    type: business
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
name: Archil
provenance_date: '2026-11-09'
provider_name: Archil
provider_slug: archil
slug: archil-eligibility
source_date: '2026-11-09'
source_filename: archil-eligibility.yml
source_heading: Eligibility
source_page: https://archil.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Archil\naid: archil\nurl: https://archil.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The company or person who accesses or uses the Product.\n- type: business\n  text: If you are accessing or using the Product on behalf of your company, you represent that you are authorized\n    to accept this Agreement on behalf of your company.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/archil/eligibility/archil-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Archil's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cloud Storage
- Filesystem
- Object Storage
- Artificial Intelligence
- Infrastructure
- Developer Tools
- Serverless
- Data
- S3
---
