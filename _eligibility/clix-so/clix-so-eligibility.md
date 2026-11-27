---
api_specs:
- filename: clix-so-clixexternalservice-api-openapi.yml
  format: yaml
  label: Clix Clix External Service API
  slug: clix-so-clixexternalservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clix-so/openapi/clix-so-clixexternalservice-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Services on behalf of an organization, you're agreeing to these Terms for that organization and confirming that you have the authority to bind that organization.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Spam, abuse, illegal content
    text: Use the Services for spam, abuse, or illegal content;
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
name: Clix
provenance_date: '2026-11-09'
provider_name: Clix
provider_slug: clix-so
slug: clix-so-eligibility
source_date: '2026-11-09'
source_filename: clix-so-eligibility.yml
source_heading: Eligibility
source_page: https://clix.so/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clix\naid: clix-so\nurl: https://clix.so/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Services on behalf of an organization, you're agreeing to these Terms for that organization\n    and confirming that you have the authority to bind that organization.\nrestricted_uses:\n- summary: Spam, abuse, illegal content\n  text: Use the Services for spam, abuse, or illegal content;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/clix-so/eligibility/clix-so-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Clix's own page on 2026-11-09.
synthetic: false
tags:
- Push Notifications
- Mobile
- Messaging
- Campaigns
- Event Tracking
- Customer Engagement
- A2A
- MCP
- Agents
- SDK
- United States
- Company
---
