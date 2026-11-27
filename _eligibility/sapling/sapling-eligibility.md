---
api_specs:
- filename: sapling-account-api-openapi.yml
  format: yaml
  label: Sapling Account API
  slug: sapling-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sapling/openapi/sapling-account-api-openapi.yml
- filename: sapling-analysis-api-openapi.yml
  format: yaml
  label: Sapling Analysis API
  slug: sapling-analysis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sapling/openapi/sapling-analysis-api-openapi.yml
- filename: sapling-detection-api-openapi.yml
  format: yaml
  label: Sapling Detection API
  slug: sapling-detection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sapling/openapi/sapling-detection-api-openapi.yml
- filename: sapling-files-api-openapi.yml
  format: yaml
  label: Sapling Files API
  slug: sapling-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sapling/openapi/sapling-files-api-openapi.yml
- filename: sapling-generation-api-openapi.yml
  format: yaml
  label: Sapling Generation API
  slug: sapling-generation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sapling/openapi/sapling-generation-api-openapi.yml
- filename: sapling-proofreading-api-openapi.yml
  format: yaml
  label: Sapling Proofreading API
  slug: sapling-proofreading-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sapling/openapi/sapling-proofreading-api-openapi.yml
- filename: sapling-service-api-openapi.yml
  format: yaml
  label: Sapling Service API
  slug: sapling-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sapling/openapi/sapling-service-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: YOU MUST BE AT LEAST 13 YEARS OLD TO USE THE SERVICE. BY AGREEING TO THESE TERMS YOU REPRESENT AND WARRANT THAT YOU ARE AT LEAST 18 YEARS OLD, OR, IF YOU ARE BETWEEN 13 AND 17 YEARS OLD, THAT YOU ARE USING THE SERVICE ONLY WITH THE APPROVAL OF YOUR PARENT OR GUARDIAN
    value: '13'
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
name: Sapling
provenance_date: '2026-11-10'
provider_name: Sapling
provider_slug: sapling
slug: sapling-eligibility
source_date: '2026-11-10'
source_filename: sapling-eligibility.yml
source_heading: Eligibility
source_page: https://sapling.ai/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sapling\naid: sapling\nurl: https://sapling.ai/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: YOU MUST BE AT LEAST 13 YEARS OLD TO USE THE SERVICE. BY AGREEING TO THESE TERMS YOU REPRESENT AND WARRANT\n    THAT YOU ARE AT LEAST 18 YEARS OLD, OR, IF YOU ARE BETWEEN 13 AND 17 YEARS OLD, THAT YOU ARE USING THE SERVICE\n    ONLY WITH THE APPROVAL OF YOUR PARENT OR GUARDIAN\n"
source_yaml_url: https://artifacts.apis.io/sapling/eligibility/sapling-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from Sapling's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Language-Model
- Enterprise
- Productivity
---
