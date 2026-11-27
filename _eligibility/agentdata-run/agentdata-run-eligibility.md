---
api_specs:
- filename: agentdata-run-openapi-generated.yml
  format: yaml
  label: AgentData API
  slug: agentdata-run-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentdata-run/openapi/_ae-authored/agentdata-run-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Be at least 18 years old
    type: individual
  - text: Team members must work for the same organisation as the account owner.
    type: business
  minimum_age:
    text: Be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Unlawful or abusive uses
    text: Use data obtained from AgentData for spam, harassment, discrimination, or any unlawful purpose
  - summary: Data protection violations
    text: Use data in any manner that violates applicable data protection laws, including the UK GDPR, EU GDPR, or CCPA
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
name: AgentData
provenance_date: '2026-11-09'
provider_name: AgentData
provider_slug: agentdata-run
slug: agentdata-run-eligibility
source_date: '2026-11-09'
source_filename: agentdata-run-eligibility.yml
source_heading: Eligibility
source_page: https://useagentdata.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AgentData\naid: agentdata-run\nurl: https://useagentdata.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Be at least 18 years old\n- type: business\n  text: Team members must work for the same organisation as the account owner.\nrestricted_uses:\n- summary: Unlawful or abusive uses\n  text: Use data obtained from AgentData for spam, harassment, discrimination, or any unlawful purpose\n- summary: Data protection violations\n  text: Use data in any manner that violates applicable data protection laws, including the UK\
  \ GDPR, EU GDPR, or\n    CCPA\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/agentdata-run/eligibility/agentdata-run-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from AgentData's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
