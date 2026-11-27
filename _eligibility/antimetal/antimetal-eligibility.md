---
api_specs:
- filename: antimetal-artifacts-api-openapi.yml
  format: yaml
  label: Antimetal Artifacts API
  slug: antimetal-artifacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/antimetal/openapi/antimetal-artifacts-api-openapi.yml
- filename: antimetal-issues-api-openapi.yml
  format: yaml
  label: Antimetal Issues API
  slug: antimetal-issues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/antimetal/openapi/antimetal-issues-api-openapi.yml
- filename: antimetal-query-api-openapi.yml
  format: yaml
  label: Antimetal Query API
  slug: antimetal-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/antimetal/openapi/antimetal-query-api-openapi.yml
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
  - summary: Not for time- or mission-critical functions
    text: the Antimetal Platform will not be used, and are not licensed for use, in connection with any of Customer's time-critical or mission-critical functions.
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
name: Antimetal
provenance_date: '2026-11-09'
provider_name: Antimetal
provider_slug: antimetal
slug: antimetal-eligibility
source_date: '2026-11-09'
source_filename: antimetal-eligibility.yml
source_heading: Eligibility
source_page: https://antimetal.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Antimetal\naid: antimetal\nurl: https://antimetal.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Not for time- or mission-critical functions\n  text: the Antimetal Platform will not be used, and are not licensed for use, in connection with any of Customer's\n    time-critical or mission-critical functions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/antimetal/eligibility/antimetal-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Antimetal's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Observability
- Incident Management
- Site Reliability Engineering
- Artificial Intelligence
- Agents
- DevOps
- Cloud Infrastructure
- Kubernetes
- Root Cause Analysis
- MCP
- A2A
---
