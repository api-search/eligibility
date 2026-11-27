---
api_specs:
- filename: butterbase-ai-openapi-generated.yml
  format: yaml
  label: Butterbase API
  slug: butterbase-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/butterbase-ai/openapi/_ae-authored/butterbase-ai-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to create an account.
    type: individual
  - text: If you are using Butterbase on behalf of a company or organisation, you confirm you have authority to bind that entity.
    type: business
  minimum_age:
    text: You must be at least 18 years old to create an account.
    value: '18'
  restricted_uses:
  - summary: Illegal or harmful content
    text: Store or transmit illegal, harmful, or infringing content
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
name: Butterbase
provenance_date: '2026-11-09'
provider_name: Butterbase
provider_slug: butterbase-ai
slug: butterbase-ai-eligibility
source_date: '2026-11-09'
source_filename: butterbase-ai-eligibility.yml
source_heading: Eligibility
source_page: https://butterbase.ai/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Butterbase\naid: butterbase-ai\nurl: https://butterbase.ai/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to create an account.\n- type: business\n  text: If you are using Butterbase on behalf of a company or organisation, you confirm you have authority to bind\n    that entity.\nrestricted_uses:\n- summary: Illegal or harmful content\n  text: Store or transmit illegal, harmful, or infringing content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to create an account.\n"
source_yaml_url: https://artifacts.apis.io/butterbase-ai/eligibility/butterbase-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Butterbase's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Backend
- Business
- Agent-Native
- Platform
---
