---
api_specs:
- filename: chinaapi-ai-openapi-generated.yml
  format: yaml
  label: ChinaAPI API
  slug: chinaapi-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chinaapi-ai/openapi/_ae-authored/chinaapi-ai-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to form a binding contract.
    type: individual
  - text: If you use the Service on behalf of an organization, you represent that you are authorized to bind it.
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to form a binding contract.
    value: '18'
  restricted_uses:
  - summary: Violating law or third-party rights
    text: violate any applicable law or regulation, or infringe the rights of others
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
name: ChinaAPI
provenance_date: '2026-11-09'
provider_name: ChinaAPI
provider_slug: chinaapi-ai
slug: chinaapi-ai-eligibility
source_date: '2026-11-09'
source_filename: chinaapi-ai-eligibility.yml
source_heading: Eligibility
source_page: https://chinaapi.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ChinaAPI\naid: chinaapi-ai\nurl: https://chinaapi.ai/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to form a binding contract.\n- type: business\n  text: If you use the Service on behalf of an organization, you represent that you are authorized to bind it.\nrestricted_uses:\n- summary: Violating law or third-party rights\n  text: violate any applicable law or regulation, or infringe the rights of others\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/chinaapi-ai/eligibility/chinaapi-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from ChinaAPI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- LLM
- API Gateway
- OpenAI-Compatible
- Video Generation
- Image Generation
- Speech
- MCP
- China
---
