---
api_specs:
- filename: fastgpu-matching-api-openapi.yml
  format: yaml
  label: FastGPU Matching API
  slug: fastgpu-matching-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastgpu/openapi/fastgpu-matching-api-openapi.yml
- filename: fastgpu-prices-api-openapi.yml
  format: yaml
  label: FastGPU Prices API
  slug: fastgpu-prices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastgpu/openapi/fastgpu-prices-api-openapi.yml
- filename: fastgpu-router-api-openapi.yml
  format: yaml
  label: FastGPU Router API
  slug: fastgpu-router-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastgpu/openapi/fastgpu-router-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Service only if you can form a legally binding contract with us
    type: individual
  - text: If you use the Service on behalf of a company or other organization, you represent that you have authority to bind that entity to these Terms
    type: business
  minimum_age:
    text: You may use it only if you meet the minimum age required to consent to the processing of your personal data in your country, or the age of majority where that is higher.
    value: null
  restricted_uses:
  - summary: Standalone data product
    text: Offering the data as a standalone data product (a price feed, dataset or API whose main content is this data).
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
name: FastGPU
provenance_date: '2026-11-09'
provider_name: FastGPU
provider_slug: fastgpu
slug: fastgpu-eligibility
source_date: '2026-11-09'
source_filename: fastgpu-eligibility.yml
source_heading: Eligibility
source_page: https://fastgpu.co/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FastGPU\naid: fastgpu\nurl: https://fastgpu.co/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Service only if you can form a legally binding contract with us\n- type: business\n  text: If you use the Service on behalf of a company or other organization, you represent that you have authority\n    to bind that entity to these Terms\nrestricted_uses:\n- summary: Standalone data product\n  text: Offering the data as a standalone data product (a price feed, dataset or API whose main content is this\n    data).\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You may use it only if you meet the minimum age required to consent to the processing of your personal data\n    in your country, or the age of majority where that is higher.\n"
source_yaml_url: https://artifacts.apis.io/fastgpu/eligibility/fastgpu-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from FastGPU's own page on 2026-11-09.
synthetic: false
tags:
- Company
- GPU
- Cloud
- Pricing
- Artificial Intelligence
---
