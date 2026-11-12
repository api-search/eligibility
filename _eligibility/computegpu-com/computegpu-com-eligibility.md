---
api_specs:
- filename: computegpu-com-gpu-api-openapi.yml
  format: yaml
  label: ComputeGpu Gpu API
  slug: computegpu-com-gpu-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computegpu-com/openapi/computegpu-com-gpu-api-openapi.yml
- filename: computegpu-com-signup-api-openapi.yml
  format: yaml
  label: ComputeGpu Signup API
  slug: computegpu-com-signup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computegpu-com/openapi/computegpu-com-signup-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful purposes
    text: Use the Service for any unlawful purpose or in violation of any applicable laws
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
name: ComputeGpu
provenance_date: '2026-11-09'
provider_name: ComputeGpu
provider_slug: computegpu-com
slug: computegpu-com-eligibility
source_date: '2026-11-09'
source_filename: computegpu-com-eligibility.yml
source_heading: Eligibility
source_page: https://computegpu.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ComputeGpu\naid: computegpu-com\nurl: https://computegpu.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful purposes\n  text: Use the Service for any unlawful purpose or in violation of any applicable laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/computegpu-com/eligibility/computegpu-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from ComputeGpu's own page on 2026-11-09.
synthetic: false
tags:
- Company
- GPU Cloud
- AI Infrastructure
- Compute
- Machine Learning
- Inference
- LLM
- MCP
- CLI
---
