---
api_specs:
- filename: fabricatedemail-com-health-api-openapi.yml
  format: yaml
  label: fabricatedemail-com Health API
  slug: fabricatedemail-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fabricatedemail-com/openapi/fabricatedemail-com-health-api-openapi.yml
- filename: fabricatedemail-com-mcp-api-openapi.yml
  format: yaml
  label: fabricatedemail-com MCP API
  slug: fabricatedemail-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fabricatedemail-com/openapi/fabricatedemail-com-mcp-api-openapi.yml
- filename: fabricatedemail-com-messages-api-openapi.yml
  format: yaml
  label: fabricatedemail-com Messages API
  slug: fabricatedemail-com-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fabricatedemail-com/openapi/fabricatedemail-com-messages-api-openapi.yml
- filename: fabricatedemail-com-subscriptions-api-openapi.yml
  format: yaml
  label: fabricatedemail-com Subscriptions API
  slug: fabricatedemail-com-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fabricatedemail-com/openapi/fabricatedemail-com-subscriptions-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: One account belongs to one person, identified by the email address they sign in with.
    type: individual
  - text: '"you" means the person or organisation holding the account.'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No outbound sending
    text: The service cannot send mail.
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
name: fabricatedemail-com
provenance_date: '2026-11-09'
provider_name: fabricatedemail-com
provider_slug: fabricatedemail-com
slug: fabricatedemail-com-eligibility
source_date: '2026-11-09'
source_filename: fabricatedemail-com-eligibility.yml
source_heading: Eligibility
source_page: https://fabricatedemail.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: fabricatedemail-com\naid: fabricatedemail-com\nurl: https://fabricatedemail.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: One account belongs to one person, identified by the email address they sign in with.\n- type: business\n  text: '\"you\" means the person or organisation holding the account.'\nrestricted_uses:\n- summary: No outbound sending\n  text: The service cannot send mail.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fabricatedemail-com/eligibility/fabricatedemail-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from fabricatedemail-com's own page on 2026-11-09.
synthetic: false
tags:
- Email
- Disposable
- Testing
- Automation
- Services
---
