---
api_specs:
- filename: agentbill-dev-openapi-generated.yml
  format: yaml
  label: AgentBill API
  slug: agentbill-dev-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentbill-dev/openapi/_ae-authored/agentbill-dev-openapi-generated.yml
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
  - summary: Illegal use and abuse
    text: Don't use the service to break the law, to abuse third-party APIs, or to attack the service itself
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You need a valid email to register.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AgentBill
provenance_date: '2026-11-09'
provider_name: AgentBill
provider_slug: agentbill-dev
slug: agentbill-dev-eligibility
source_date: '2026-11-09'
source_filename: agentbill-dev-eligibility.yml
source_heading: Eligibility
source_page: https://agentbill.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AgentBill\naid: agentbill-dev\nurl: https://agentbill.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal use and abuse\n  text: Don't use the service to break the law, to abuse third-party APIs, or to attack the service itself\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You need a valid email to register.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentbill-dev/eligibility/agentbill-dev-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from AgentBill's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
