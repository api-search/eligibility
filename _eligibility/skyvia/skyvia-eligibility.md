---
api_specs:
- filename: index.html
  format: yaml
  label: Skyvia Public API
  slug: skyvia-public-api
  spec_type: OpenAPI
  url: https://api.skyvia.com/swagger/index.html
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The right to access the Service is revoked where these Terms of Service or use of the Service is prohibited or to the extent offering, sale or provision of the Service conflicts with any applicable law, rule or regulation.
  entity_types:
  - text: You represent and warrant that you are at least 18 years of age.
    type: individual
  minimum_age:
    text: You represent and warrant that you are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Service only for own use
    text: Further, the Service is offered only for your use and not for the use or benefit of any third-party.
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
name: Skyvia
provenance_date: '2026-11-10'
provider_name: Skyvia
provider_slug: skyvia
slug: skyvia-eligibility
source_date: '2026-11-10'
source_filename: skyvia-eligibility.yml
source_heading: Eligibility
source_page: https://skyvia.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Skyvia\naid: skyvia\nurl: https://skyvia.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The right to access the Service is revoked where these Terms of Service or use of the Service is prohibited\n    or to the extent offering, sale or provision of the Service conflicts with any applicable law, rule or regulation.\nentity_types:\n- type: individual\n  text: You represent and warrant that you are at least 18 years of age.\nrestricted_uses:\n- summary: Service only for own use\n  text: Further, the Service is offered only for your use and not for the use or benefit\
  \ of any third-party.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/skyvia/eligibility/skyvia-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Skyvia's own page on 2026-11-10.
synthetic: false
tags:
- Data Integration
- iPaaS
- ETL
- ELT
- Data Replication
- Cloud Backup
- OData
- SQL
- Workflow Automation
- No-Code
- Connectors
- Data Management
- MCP
- Agent-Native
- Data Access
---
