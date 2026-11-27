---
api_specs:
- filename: deepdna-ai-knowledge-api-openapi.yml
  format: yaml
  label: deepdna-ai Knowledge API
  slug: deepdna-ai-knowledge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepdna-ai/openapi/deepdna-ai-knowledge-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To enter into an agreement with DeepDNA, you must be at least 18 years of age and have the legal capacity to enter into a binding agreement.
    type: individual
  minimum_age:
    text: To enter into an agreement with DeepDNA, you must be at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Clinical decisions without professional
    text: that you will not use it to make or support clinical decisions without a qualified professional
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
name: deepdna-ai
provenance_date: '2026-11-09'
provider_name: deepdna-ai
provider_slug: deepdna-ai
slug: deepdna-ai-eligibility
source_date: '2026-11-09'
source_filename: deepdna-ai-eligibility.yml
source_heading: Eligibility
source_page: https://deepdna.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: deepdna-ai\naid: deepdna-ai\nurl: https://deepdna.ai/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To enter into an agreement with DeepDNA, you must be at least 18 years of age and have the legal capacity\n    to enter into a binding agreement.\nrestricted_uses:\n- summary: Clinical decisions without professional\n  text: that you will not use it to make or support clinical decisions without a qualified professional\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n\
  \  text: To enter into an agreement with DeepDNA, you must be at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/deepdna-ai/eligibility/deepdna-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from deepdna-ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Pharmacogenomics
- MCP
- AI Agents
- Genomics
- Healthcare
---
