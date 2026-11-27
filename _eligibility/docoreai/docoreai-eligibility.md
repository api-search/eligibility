---
api_specs:
- filename: docoreai-chat-completions-api-openapi.yml
  format: yaml
  label: DoCoreAI Chat Completions API
  slug: docoreai-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docoreai/openapi/docoreai-chat-completions-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old, or the age of legal majority in your jurisdiction, and have authority to bind your organisation if registering on its behalf.
    type: individual
  - text: have authority to bind your organisation if registering on its behalf
    type: business
  minimum_age:
    text: You must be at least 18 years old, or the age of legal majority in your jurisdiction
    value: '18'
  restricted_uses:
  - summary: Unlawful or sanctions-violating use
    text: Use the service for any unlawful purpose, or in violation of applicable export control or sanctions laws
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To access the DoCoreAI dashboard, telemetry aggregation, and token management features, you must register for an account using a valid work email address.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: DoCoreAI
provenance_date: '2026-11-09'
provider_name: DoCoreAI
provider_slug: docoreai
slug: docoreai-eligibility
source_date: '2026-11-09'
source_filename: docoreai-eligibility.yml
source_heading: Eligibility
source_page: https://docoreai.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DoCoreAI\naid: docoreai\nurl: https://docoreai.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old, or the age of legal majority in your jurisdiction, and have authority\n    to bind your organisation if registering on its behalf.\n- type: business\n  text: have authority to bind your organisation if registering on its behalf\nrestricted_uses:\n- summary: Unlawful or sanctions-violating use\n  text: Use the service for any unlawful purpose, or in violation of applicable export control\
  \ or sanctions laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To access the DoCoreAI dashboard, telemetry aggregation, and token management features, you must register\n    for an account using a valid work email address.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age of legal majority in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/docoreai/eligibility/docoreai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from DoCoreAI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Governance
- Cost Management
- LLM
- Software-as-a-Service
---
