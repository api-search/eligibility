---
api_specs:
- filename: agentexperiences-com-openapi-generated.yml
  format: yaml
  label: Agent Experiences API
  slug: agentexperiences-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentexperiences-com/openapi/_ae-authored/agentexperiences-com-openapi-generated.yml
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
  - summary: Agent Analyzer scans limited to owned or authorised pages
    text: Only scan pages you own or are authorised to test.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The Agent Analyzer requires an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Agent Experiences
provenance_date: '2026-11-09'
provider_name: Agent Experiences
provider_slug: agentexperiences-com
slug: agentexperiences-com-eligibility
source_date: '2026-11-09'
source_filename: agentexperiences-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.agentexperiences.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agent Experiences\naid: agentexperiences-com\nurl: https://www.agentexperiences.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Agent Analyzer scans limited to owned or authorised pages\n  text: Only scan pages you own or are authorised to test.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The Agent Analyzer requires an account.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentexperiences-com/eligibility/agentexperiences-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Agent Experiences's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Agent Experience
- Optimization
- Consulting
- Technology
---
