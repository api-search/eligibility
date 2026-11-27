---
api_specs:
- filename: reachdesk-bulk-sends-api-openapi.yml
  format: yaml
  label: Reachdesk Bulk Sends API
  slug: reachdesk-bulk-sends-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reachdesk/openapi/reachdesk-bulk-sends-api-openapi.yml
- filename: reachdesk-campaigns-api-openapi.yml
  format: yaml
  label: Reachdesk Campaigns API
  slug: reachdesk-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reachdesk/openapi/reachdesk-campaigns-api-openapi.yml
- filename: reachdesk-contacts-api-openapi.yml
  format: yaml
  label: Reachdesk Contacts API
  slug: reachdesk-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reachdesk/openapi/reachdesk-contacts-api-openapi.yml
- filename: reachdesk-gdpr-api-openapi.yml
  format: yaml
  label: Reachdesk Gdpr API
  slug: reachdesk-gdpr-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reachdesk/openapi/reachdesk-gdpr-api-openapi.yml
- filename: reachdesk-organization-api-openapi.yml
  format: yaml
  label: Reachdesk Organization API
  slug: reachdesk-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reachdesk/openapi/reachdesk-organization-api-openapi.yml
- filename: reachdesk-sends-api-openapi.yml
  format: yaml
  label: Reachdesk Sends API
  slug: reachdesk-sends-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reachdesk/openapi/reachdesk-sends-api-openapi.yml
- filename: reachdesk-transactions-api-openapi.yml
  format: yaml
  label: Reachdesk Transactions API
  slug: reachdesk-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reachdesk/openapi/reachdesk-transactions-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years of age to use our Site.
    value: '18'
  restricted_uses:
  - summary: Data mining or harvesting
    text: Engaging in any data mining, data harvesting, data extracting or any other similar activity in relation to this Website, or while using this Website;
  - summary: Advertising or marketing use
    text: Using this Website to engage in any advertising or marketing.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The validity of the email address is verified by Reachdesk.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Reachdesk
provenance_date: '2026-11-10'
provider_name: Reachdesk
provider_slug: reachdesk
slug: reachdesk-eligibility
source_date: '2026-11-10'
source_filename: reachdesk-eligibility.yml
source_heading: Eligibility
source_page: https://www.reachdesk.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Reachdesk\naid: reachdesk\nurl: https://www.reachdesk.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Data mining or harvesting\n  text: Engaging in any data mining, data harvesting, data extracting or any other similar activity in relation\n    to this Website, or while using this Website;\n- summary: Advertising or marketing use\n  text: Using this Website to engage in any advertising or marketing.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The validity of the email address\
  \ is verified by Reachdesk.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use our Site.\n"
source_yaml_url: https://artifacts.apis.io/reachdesk/eligibility/reachdesk-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Reachdesk's own page on 2026-11-10.
synthetic: false
tags:
- Corporate Gifting
- Direct Mail
- Swag
- B2B
- Sales Enablement
- Customer Success
- Marketing Automation
- Gifting Platform
- Rewards
- MCP
- AI Agents
- OpenAPI
---
