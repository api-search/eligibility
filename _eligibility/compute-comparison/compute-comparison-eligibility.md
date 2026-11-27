---
api_specs:
- filename: compute-comparison-prices-api-openapi.yml
  format: yaml
  label: Compute Comparison Prices API
  slug: compute-comparison-prices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compute-comparison/openapi/compute-comparison-prices-api-openapi.yml
- filename: compute-comparison-status-api-openapi.yml
  format: yaml
  label: Compute Comparison Status API
  slug: compute-comparison-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compute-comparison/openapi/compute-comparison-status-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: an agreement between Compute Comparison and the individuals that use the Sites
    type: individual
  - text: If you use or access the Sites on behalf of a business or other entity, you must have authority to bind that business/entity.
    type: business
  minimum_age:
    text: IF YOU ARE UNDER THE AGE OF 18 (A MINOR), YOUR PARENT OR LEGAL GUARDIAN MUST READ AND CONSENT TO THE TERMS OF USE BEFORE YOU USE THE SITES.
    value: '18'
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
name: Compute Comparison
provenance_date: '2026-11-09'
provider_name: Compute Comparison
provider_slug: compute-comparison
slug: compute-comparison-eligibility
source_date: '2026-11-09'
source_filename: compute-comparison-eligibility.yml
source_heading: Eligibility
source_page: https://computecomparison.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Compute Comparison\naid: compute-comparison\nurl: https://computecomparison.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: an agreement between Compute Comparison and the individuals that use the Sites\n- type: business\n  text: If you use or access the Sites on behalf of a business or other entity, you must have authority to bind\n    that business/entity.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: IF YOU ARE UNDER THE AGE\
  \ OF 18 (A MINOR), YOUR PARENT OR LEGAL GUARDIAN MUST READ AND CONSENT TO THE TERMS\n    OF USE BEFORE YOU USE THE SITES.\n"
source_yaml_url: https://artifacts.apis.io/compute-comparison/eligibility/compute-comparison-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Compute Comparison's own page on 2026-11-09.
synthetic: false
tags:
- Company
- GPU
- LLM
- Cloud
- Pricing
- Comparison
---
