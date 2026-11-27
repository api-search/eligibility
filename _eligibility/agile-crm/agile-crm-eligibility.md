---
api_specs:
- filename: agile-crm-campaigns-api-openapi.yml
  format: yaml
  label: Agile CRM Campaigns API
  slug: agile-crm-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agile-crm/openapi/agile-crm-campaigns-api-openapi.yml
- filename: agile-crm-companies-api-openapi.yml
  format: yaml
  label: Agile CRM Companies API
  slug: agile-crm-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agile-crm/openapi/agile-crm-companies-api-openapi.yml
- filename: agile-crm-contacts-api-openapi.yml
  format: yaml
  label: Agile CRM Contacts API
  slug: agile-crm-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agile-crm/openapi/agile-crm-contacts-api-openapi.yml
- filename: agile-crm-deals-api-openapi.yml
  format: yaml
  label: Agile CRM Deals API
  slug: agile-crm-deals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agile-crm/openapi/agile-crm-deals-api-openapi.yml
- filename: agile-crm-documents-api-openapi.yml
  format: yaml
  label: Agile CRM Documents API
  slug: agile-crm-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agile-crm/openapi/agile-crm-documents-api-openapi.yml
- filename: agile-crm-events-api-openapi.yml
  format: yaml
  label: Agile CRM Events API
  slug: agile-crm-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agile-crm/openapi/agile-crm-events-api-openapi.yml
- filename: agile-crm-helpdesk-api-openapi.yml
  format: yaml
  label: Agile CRM HelpDesk API
  slug: agile-crm-helpdesk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agile-crm/openapi/agile-crm-helpdesk-api-openapi.yml
- filename: agile-crm-notes-api-openapi.yml
  format: yaml
  label: Agile CRM Notes API
  slug: agile-crm-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agile-crm/openapi/agile-crm-notes-api-openapi.yml
- filename: agile-crm-tasks-api-openapi.yml
  format: yaml
  label: Agile CRM Tasks API
  slug: agile-crm-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agile-crm/openapi/agile-crm-tasks-api-openapi.yml
- filename: agile-crm-tracks-api-openapi.yml
  format: yaml
  label: Agile CRM Tracks API
  slug: agile-crm-tracks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agile-crm/openapi/agile-crm-tracks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must provide your legal full name, a valid business email address, and any other information requested in order to complete the sign up process.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Spam
    text: You may not use the service to store, host, or send unsolicited email (spam), chats or SMS messages.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We reserve the rights to accept or refuse to any potential client. We have the sole discretion on whether to allow you to register, renew, change plan, or use our services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Agile CRM
provenance_date: '2026-11-09'
provider_name: Agile CRM
provider_slug: agile-crm
slug: agile-crm-eligibility
source_date: '2026-11-09'
source_filename: agile-crm-eligibility.yml
source_heading: Eligibility
source_page: https://www.agilecrm.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agile CRM\naid: agile-crm\nurl: https://www.agilecrm.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You must provide your legal full name, a valid business email address, and any other information requested\n    in order to complete the sign up process.\nrestricted_uses:\n- summary: Spam\n  text: You may not use the service to store, host, or send unsolicited email (spam), chats or SMS messages.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: We reserve the rights to accept or refuse to any potential\
  \ client. We have the sole discretion on whether\n    to allow you to register, renew, change plan, or use our services.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agile-crm/eligibility/agile-crm-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Agile CRM's own page on 2026-11-09.
synthetic: false
tags:
- CRM
- Sales Automation
- Marketing Automation
- Help Desk
- Small Business
- Contact Management
---
