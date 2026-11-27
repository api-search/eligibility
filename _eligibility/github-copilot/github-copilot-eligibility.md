---
api_specs:
- filename: github-copilot-copilot-api-openapi.yml
  format: yaml
  label: GitHub Copilot Copilot API
  slug: github-copilot-copilot-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/github-copilot/openapi/github-copilot-copilot-api-openapi.yml
- filename: github-copilot-copilot-spaces-api-openapi.yml
  format: yaml
  label: GitHub Copilot Copilot Spaces API
  slug: github-copilot-copilot-spaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/github-copilot/openapi/github-copilot-copilot-spaces-api-openapi.yml
- filename: github-copilot-merge-queue-api-openapi.yml
  format: yaml
  label: GitHub Copilot Merge Queue API
  slug: github-copilot-merge-queue-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/github-copilot/openapi/github-copilot-merge-queue-api-openapi.yml
- filename: github-copilot-pulls-api-openapi.yml
  format: yaml
  label: GitHub Copilot Pulls API
  slug: github-copilot-pulls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/github-copilot/openapi/github-copilot-pulls-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be a human to create an Account.
    type: individual
  - text: Special terms may apply for business or government Accounts
    type: business
  minimum_age:
    text: You must be age 13 or older.
    value: '13'
  restricted_uses:
  - summary: Sanctioned persons and export controls
    text: You may not use GitHub if you are or are working on behalf of a Specially Designated National (SDN)
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide a valid email address in order to complete the signup process.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: GitHub Copilot
provenance_date: '2026-11-09'
provider_name: GitHub Copilot
provider_slug: github-copilot
slug: github-copilot-eligibility
source_date: '2026-11-09'
source_filename: github-copilot-eligibility.yml
source_heading: Eligibility
source_page: https://docs.github.com/en/site-policy/github-terms/github-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GitHub Copilot\naid: github-copilot\nurl: https://docs.github.com/en/site-policy/github-terms/github-terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be a human to create an Account.\n- type: business\n  text: Special terms may apply for business or government Accounts\nrestricted_uses:\n- summary: Sanctioned persons and export controls\n  text: You may not use GitHub if you are or are working on behalf of a Specially Designated National (SDN)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: You must provide a valid email address in order to complete the signup process.\nminimum_age:\n  value: '13'\n  text: You must be age 13 or older.\n"
source_yaml_url: https://artifacts.apis.io/github-copilot/eligibility/github-copilot-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from GitHub Copilot's own page on 2026-11-09.
synthetic: false
tags:
- Agents
- Artificial Intelligence
- Code Generation
- Code Review
- Coding Agents
- Custom Instructions
- Developer Tools
- Extensions
- IDE
- Machine Learning
- MCP
- Metrics
- Productivity
---
