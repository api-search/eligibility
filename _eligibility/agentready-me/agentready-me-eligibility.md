---
api_specs:
- filename: agentready-me-commerce-api-openapi.yml
  format: yaml
  label: AgentReady.me Commerce API
  slug: agentready-me-commerce-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentready-me/openapi/agentready-me-commerce-api-openapi.yml
- filename: agentready-me-diagnostics-api-openapi.yml
  format: yaml
  label: AgentReady.me Diagnostics API
  slug: agentready-me-diagnostics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentready-me/openapi/agentready-me-diagnostics-api-openapi.yml
- filename: agentready-me-scans-api-openapi.yml
  format: yaml
  label: AgentReady.me Scans API
  slug: agentready-me-scans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentready-me/openapi/agentready-me-scans-api-openapi.yml
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
  - summary: Unlawful activity and unauthorized scanning
    text: using AgentReady for unlawful activity
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
name: AgentReady.me
provenance_date: '2026-11-09'
provider_name: AgentReady.me
provider_slug: agentready-me
slug: agentready-me-eligibility
source_date: '2026-11-09'
source_filename: agentready-me-eligibility.yml
source_heading: Eligibility
source_page: https://www.agentready.me/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AgentReady.me\naid: agentready-me\nurl: https://www.agentready.me/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful activity and unauthorized scanning\n  text: using AgentReady for unlawful activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentready-me/eligibility/agentready-me-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from AgentReady.me's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Agent Readiness
- WebAudit
- SEO
- Platform
---
