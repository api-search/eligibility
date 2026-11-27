---
api_specs:
- filename: fastino-labs-anthropic-compat-api-openapi.yml
  format: yaml
  label: Fastino Labs Anthropic Compat API
  slug: fastino-labs-anthropic-compat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastino-labs/openapi/fastino-labs-anthropic-compat-api-openapi.yml
- filename: fastino-labs-inference-api-openapi.yml
  format: yaml
  label: Fastino Labs Inference API
  slug: fastino-labs-inference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastino-labs/openapi/fastino-labs-inference-api-openapi.yml
- filename: fastino-labs-inference-history-api-openapi.yml
  format: yaml
  label: Fastino Labs Inference History API
  slug: fastino-labs-inference-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastino-labs/openapi/fastino-labs-inference-history-api-openapi.yml
- filename: fastino-labs-openai-compat-api-openapi.yml
  format: yaml
  label: Fastino Labs Openai Compat API
  slug: fastino-labs-openai-compat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastino-labs/openapi/fastino-labs-openai-compat-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the platform on behalf of a company or other organization, you represent that you are authorized to accept these Terms on its behalf
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Consequential decisions without human oversight
    text: Use platform outputs as the sole basis for consequential decisions in healthcare, legal, financial, employment, housing, or law enforcement contexts without appropriate human oversight.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: A verified payment method is required to access inference services. The verification step is used for identity verification and abuse prevention
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Fastino Labs
provenance_date: '2026-11-09'
provider_name: Fastino Labs
provider_slug: fastino-labs
slug: fastino-labs-eligibility
source_date: '2026-11-09'
source_filename: fastino-labs-eligibility.yml
source_heading: Eligibility
source_page: https://agent.fastino.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fastino Labs\naid: fastino-labs\nurl: https://agent.fastino.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the platform on behalf of a company or other organization, you represent that you are authorized\n    to accept these Terms on its behalf\nrestricted_uses:\n- summary: Consequential decisions without human oversight\n  text: Use platform outputs as the sole basis for consequential decisions in healthcare, legal, financial, employment,\n    housing, or law enforcement contexts without appropriate human oversight.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: A verified payment method is required to access inference services. The verification step is used for identity\n    verification and abuse prevention\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fastino-labs/eligibility/fastino-labs-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Fastino Labs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Small Language Models
- Fine-Tuning
- Inference
- Named Entity Recognition
- Information Extraction
- LLM
- Agents
- PII Detection
- Model Training
- Foundation Models
---
