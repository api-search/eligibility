---
api_specs:
- filename: hunta-ai-admin-api-openapi.yml
  format: yaml
  label: hunta-ai Admin API
  slug: hunta-ai-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunta-ai/openapi/hunta-ai-admin-api-openapi.yml
- filename: hunta-ai-candidates-api-openapi.yml
  format: yaml
  label: hunta-ai Candidates API
  slug: hunta-ai-candidates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunta-ai/openapi/hunta-ai-candidates-api-openapi.yml
- filename: hunta-ai-errata-api-openapi.yml
  format: yaml
  label: hunta-ai Errata API
  slug: hunta-ai-errata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunta-ai/openapi/hunta-ai-errata-api-openapi.yml
- filename: hunta-ai-export-api-openapi.yml
  format: yaml
  label: hunta-ai Export API
  slug: hunta-ai-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunta-ai/openapi/hunta-ai-export-api-openapi.yml
- filename: hunta-ai-facts-api-openapi.yml
  format: yaml
  label: hunta-ai Facts API
  slug: hunta-ai-facts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunta-ai/openapi/hunta-ai-facts-api-openapi.yml
- filename: hunta-ai-memories-api-openapi.yml
  format: yaml
  label: hunta-ai Memories API
  slug: hunta-ai-memories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunta-ai/openapi/hunta-ai-memories-api-openapi.yml
- filename: hunta-ai-metrics-api-openapi.yml
  format: yaml
  label: hunta-ai Metrics API
  slug: hunta-ai-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunta-ai/openapi/hunta-ai-metrics-api-openapi.yml
- filename: hunta-ai-reckon-api-openapi.yml
  format: yaml
  label: hunta-ai Reckon API
  slug: hunta-ai-reckon-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunta-ai/openapi/hunta-ai-reckon-api-openapi.yml
- filename: hunta-ai-reconcile-api-openapi.yml
  format: yaml
  label: hunta-ai Reconcile API
  slug: hunta-ai-reconcile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunta-ai/openapi/hunta-ai-reconcile-api-openapi.yml
- filename: hunta-ai-whoami-api-openapi.yml
  format: yaml
  label: hunta-ai Whoami API
  slug: hunta-ai-whoami-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunta-ai/openapi/hunta-ai-whoami-api-openapi.yml
claim_count: 2
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
  - summary: Unlawful use
    text: No unlawful content or use
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You sign in with a third-party identity (GitHub or Google) and receive an isolated tenant.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: hunta-ai
provenance_date: '2026-11-09'
provider_name: hunta-ai
provider_slug: hunta-ai
slug: hunta-ai-eligibility
source_date: '2026-11-09'
source_filename: hunta-ai-eligibility.yml
source_heading: Eligibility
source_page: https://hunta.ai/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: hunta-ai\naid: hunta-ai\nurl: https://hunta.ai/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful use\n  text: No unlawful content or use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You sign in with a third-party identity (GitHub or Google) and receive an isolated tenant.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hunta-ai/eligibility/hunta-ai-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from hunta-ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Memory
- MCP
- Attestable
---
