---
api_specs:
- filename: agent-tune-com-openapi-generated.yml
  format: yaml
  label: AgentTune API
  slug: agent-tune-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agent-tune-com/openapi/_ae-authored/agent-tune-com-openapi-generated.yml
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
  - summary: No professional advice presentation
    text: don’t present AgentTune’s outputs to others as professional advice.
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
name: AgentTune
provenance_date: '2026-11-09'
provider_name: AgentTune
provider_slug: agent-tune-com
slug: agent-tune-com-eligibility
source_date: '2026-11-09'
source_filename: agent-tune-com-eligibility.yml
source_heading: Eligibility
source_page: https://agent-tune.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AgentTune\naid: agent-tune-com\nurl: https://agent-tune.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No professional advice presentation\n  text: don’t present AgentTune’s outputs to others as professional advice.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agent-tune-com/eligibility/agent-tune-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from AgentTune's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
