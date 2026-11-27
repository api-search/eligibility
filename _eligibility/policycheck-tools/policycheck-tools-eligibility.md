---
api_specs:
- filename: policycheck-tools-chatgpt-api-openapi.yml
  format: yaml
  label: PolicyCheck Chatgpt API
  slug: policycheck-tools-chatgpt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/policycheck-tools/openapi/policycheck-tools-chatgpt-api-openapi.yml
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
  - summary: No illegal or harmful content
    text: Not use the service to analyze illegal or harmful content
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
name: PolicyCheck
provenance_date: '2026-11-10'
provider_name: PolicyCheck
provider_slug: policycheck-tools
slug: policycheck-tools-eligibility
source_date: '2026-11-10'
source_filename: policycheck-tools-eligibility.yml
source_heading: Eligibility
source_page: https://policycheck.tools/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PolicyCheck\naid: policycheck-tools\nurl: https://policycheck.tools/legal\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No illegal or harmful content\n  text: Not use the service to analyze illegal or harmful content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/policycheck-tools/eligibility/policycheck-tools-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from PolicyCheck's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Policy Analysis
- Consumer Protection
- E-Commerce
- Agentic Commerce
- Risk Assessment
- AI Agents
- A2A
- MCP
- x402
- Legal
- Returns
---
