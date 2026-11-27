---
api_specs:
- filename: agentdrive-sh-openapi-generated.yml
  format: yaml
  label: AgentDrive API
  slug: agentdrive-sh-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentdrive-sh/openapi/_ae-authored/agentdrive-sh-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 16 years old.
    value: '16'
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: You may register anonymously (an API key is issued via /v1/register without an email) or claim an account via email magic-link, Google, or GitHub OAuth.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AgentDrive
provenance_date: '2026-11-09'
provider_name: AgentDrive
provider_slug: agentdrive-sh
slug: agentdrive-sh-eligibility
source_date: '2026-11-09'
source_filename: agentdrive-sh-eligibility.yml
source_heading: Eligibility
source_page: https://agentdrive.sh/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AgentDrive\naid: agentdrive-sh\nurl: https://agentdrive.sh/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: You may register anonymously (an API key is issued via /v1/register without an email) or claim an account\n    via email magic-link, Google, or GitHub OAuth.\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old.\n"
source_yaml_url: https://artifacts.apis.io/agentdrive-sh/eligibility/agentdrive-sh-eligibility.yml
stated_fields:
- verification
- minimum_age
summary_line: 2 quoted statements, read from AgentDrive's own page on 2026-11-09.
synthetic: false
tags:
- AgentDrive
- Artificial Intelligence
- Multi-Agent
- Workspace
- Memory
- MCP
---
