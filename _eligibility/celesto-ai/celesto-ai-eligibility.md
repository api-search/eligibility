---
api_specs:
- filename: celesto-ai-agentor-openapi-generated.yml
  format: yaml
  label: Celesto AI agentor API
  slug: agentor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/celesto-ai/openapi/_ae-authored/celesto-ai-agentor-openapi-generated.yml
- filename: celesto-ai-celesto-openapi-generated.yml
  format: yaml
  label: Celesto AI celesto API
  slug: celesto-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/celesto-ai/openapi/_ae-authored/celesto-ai-celesto-openapi-generated.yml
- filename: celesto-ai-core-openapi-generated.yml
  format: yaml
  label: Celesto AI core API
  slug: core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/celesto-ai/openapi/_ae-authored/celesto-ai-core-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 16 years old (or the age of majority in your jurisdiction) to use the services.
    value: '16'
  restricted_uses:
  - summary: Regulated or high-risk workloads
    text: Do not use the services for regulated or high‑risk workloads unless we have an appropriate agreement in place.
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
name: Celesto AI
provenance_date: '2026-11-09'
provider_name: Celesto AI
provider_slug: celesto-ai
slug: celesto-ai-eligibility
source_date: '2026-11-09'
source_filename: celesto-ai-eligibility.yml
source_heading: Eligibility
source_page: https://celesto.ai/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Celesto AI\naid: celesto-ai\nurl: https://celesto.ai/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Regulated or high-risk workloads\n  text: Do not use the services for regulated or high‑risk workloads unless we have an appropriate agreement in\n    place.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old (or the age of majority in your jurisdiction) to use the services.\n"
source_yaml_url: https://artifacts.apis.io/celesto-ai/eligibility/celesto-ai-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Celesto AI's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- CI
- Runners
- Cloud
- Automation
- Company
---
