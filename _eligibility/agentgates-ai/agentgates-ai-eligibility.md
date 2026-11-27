---
api_specs:
- filename: agentgates-ai-compute-api-openapi.yml
  format: yaml
  label: Agentgates Compute API
  slug: agentgates-ai-compute-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentgates-ai/openapi/agentgates-ai-compute-api-openapi.yml
- filename: agentgates-ai-directory-api-openapi.yml
  format: yaml
  label: Agentgates Directory API
  slug: agentgates-ai-directory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentgates-ai/openapi/agentgates-ai-directory-api-openapi.yml
- filename: agentgates-ai-inference-api-openapi.yml
  format: yaml
  label: Agentgates Inference API
  slug: agentgates-ai-inference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentgates-ai/openapi/agentgates-ai-inference-api-openapi.yml
- filename: agentgates-ai-llms-txt-api-openapi.yml
  format: yaml
  label: Agentgates Llms.txt API
  slug: agentgates-ai-llms-txt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentgates-ai/openapi/agentgates-ai-llms-txt-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 18 or older and legally able to enter this agreement.
    type: individual
  minimum_age:
    text: You must be 18 or older and legally able to enter this agreement.
    value: '18'
  restricted_uses:
  - summary: Sanctions and unlawful jurisdictions
    text: You may not use the service where the law forbids it, and you may not buy on behalf of anyone on a sanctions list.
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
name: Agentgates
provenance_date: '2026-11-09'
provider_name: Agentgates
provider_slug: agentgates-ai
slug: agentgates-ai-eligibility
source_date: '2026-11-09'
source_filename: agentgates-ai-eligibility.yml
source_heading: Eligibility
source_page: https://agentgates.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agentgates\naid: agentgates-ai\nurl: https://agentgates.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be 18 or older and legally able to enter this agreement.\nrestricted_uses:\n- summary: Sanctions and unlawful jurisdictions\n  text: You may not use the service where the law forbids it, and you may not buy on behalf of anyone on a sanctions\n    list.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 or older and legally able to\
  \ enter this agreement.\n"
source_yaml_url: https://artifacts.apis.io/agentgates-ai/eligibility/agentgates-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Agentgates's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Compute
- Inference
- Blockchain
- Payments
---
