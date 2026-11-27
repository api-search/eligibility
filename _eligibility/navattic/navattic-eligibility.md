---
api_specs:
- filename: navattic-health-api-openapi.yml
  format: yaml
  label: Navattic Health API
  slug: navattic-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/navattic/openapi/navattic-health-api-openapi.yml
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
  - summary: AI Features with sensitive data
    text: Customer shall not use AI Features to process, store, or interact with personally identifiable information, protected health information, financial account data, or any other sensitive or regulated data;
  - summary: AI Features on live environments
    text: Customer shall not use AI Features to access live customer environments, or any system containing real user data;
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
name: Navattic
provenance_date: '2026-11-10'
provider_name: Navattic
provider_slug: navattic
slug: navattic-eligibility
source_date: '2026-11-10'
source_filename: navattic-eligibility.yml
source_heading: Eligibility
source_page: https://www.navattic.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Navattic\naid: navattic\nurl: https://www.navattic.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: AI Features with sensitive data\n  text: Customer shall not use AI Features to process, store, or interact with personally identifiable information,\n    protected health information, financial account data, or any other sensitive or regulated data;\n- summary: AI Features on live environments\n  text: Customer shall not use AI Features to access live customer environments, or any system containing real user\n    data;\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/navattic/eligibility/navattic-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Navattic's own page on 2026-11-10.
synthetic: false
tags:
- Interactive Demos
- Product Demo
- Sales Enablement
- Marketing
- No-Code
- Webhook
- CRM Integration
- Sales Automation
- MCP
- Agents
- Product Analytics
- A2A
---
