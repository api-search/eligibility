---
api_specs:
- filename: pandadoc-api-logs-api-openapi.yml
  format: yaml
  label: PandaDoc API Logs API
  slug: pandadoc-api-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandadoc/openapi/pandadoc-api-logs-api-openapi.yml
- filename: pandadoc-contacts-api-openapi.yml
  format: yaml
  label: PandaDoc Contacts API
  slug: pandadoc-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandadoc/openapi/pandadoc-contacts-api-openapi.yml
- filename: pandadoc-document-attachments-api-openapi.yml
  format: yaml
  label: PandaDoc Document Attachments API
  slug: pandadoc-document-attachments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandadoc/openapi/pandadoc-document-attachments-api-openapi.yml
- filename: pandadoc-document-fields-api-openapi.yml
  format: yaml
  label: PandaDoc Document Fields API
  slug: pandadoc-document-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandadoc/openapi/pandadoc-document-fields-api-openapi.yml
- filename: pandadoc-document-link-to-crm-api-openapi.yml
  format: yaml
  label: PandaDoc Document Link to CRM API
  slug: pandadoc-document-link-to-crm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandadoc/openapi/pandadoc-document-link-to-crm-api-openapi.yml
- filename: pandadoc-document-recipients-api-openapi.yml
  format: yaml
  label: PandaDoc Document Recipients API
  slug: pandadoc-document-recipients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandadoc/openapi/pandadoc-document-recipients-api-openapi.yml
- filename: pandadoc-document-reminders-api-openapi.yml
  format: yaml
  label: PandaDoc Document Reminders API
  slug: pandadoc-document-reminders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandadoc/openapi/pandadoc-document-reminders-api-openapi.yml
- filename: pandadoc-documents-api-openapi.yml
  format: yaml
  label: PandaDoc Documents API
  slug: pandadoc-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandadoc/openapi/pandadoc-documents-api-openapi.yml
- filename: pandadoc-folders-api-openapi.yml
  format: yaml
  label: PandaDoc Folders API
  slug: pandadoc-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandadoc/openapi/pandadoc-folders-api-openapi.yml
- filename: pandadoc-forms-api-openapi.yml
  format: yaml
  label: PandaDoc Forms API
  slug: pandadoc-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandadoc/openapi/pandadoc-forms-api-openapi.yml
- filename: pandadoc-members-api-openapi.yml
  format: yaml
  label: PandaDoc Members API
  slug: pandadoc-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandadoc/openapi/pandadoc-members-api-openapi.yml
- filename: pandadoc-templates-api-openapi.yml
  format: yaml
  label: PandaDoc Templates API
  slug: pandadoc-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandadoc/openapi/pandadoc-templates-api-openapi.yml
- filename: pandadoc-webhook-events-api-openapi.yml
  format: yaml
  label: PandaDoc Webhook Events API
  slug: pandadoc-webhook-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandadoc/openapi/pandadoc-webhook-events-api-openapi.yml
- filename: pandadoc-webhook-subscriptions-api-openapi.yml
  format: yaml
  label: PandaDoc Webhook Subscriptions API
  slug: pandadoc-webhook-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandadoc/openapi/pandadoc-webhook-subscriptions-api-openapi.yml
- filename: pandadoc-workspaces-api-openapi.yml
  format: yaml
  label: PandaDoc Workspaces API
  slug: pandadoc-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandadoc/openapi/pandadoc-workspaces-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the individual or legal entity (“ Customer ”) agrees that this Agreement governs Customer’s use of PandaDoc
    type: individual
  - text: the individual or legal entity (“ Customer ”) agrees that this Agreement governs Customer’s use of PandaDoc
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Free trial use limited to internal evaluation
    text: such use is permitted only for Customer’s internal evaluation until the earlier of
  - summary: Export control restrictions
    text: Customer will not permit Users to access or use any Service, Documentation, or Customization in violation of any applicable embargo restrictions
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
name: PandaDoc
provenance_date: '2026-11-10'
provider_name: PandaDoc
provider_slug: pandadoc
slug: pandadoc-eligibility
source_date: '2026-11-10'
source_filename: pandadoc-eligibility.yml
source_heading: Eligibility
source_page: https://www.pandadoc.com/legal/master-services-agreement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PandaDoc\naid: pandadoc\nurl: https://www.pandadoc.com/legal/master-services-agreement/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: the individual or legal entity (“ Customer ”) agrees that this Agreement governs Customer’s use of PandaDoc\n- type: business\n  text: the individual or legal entity (“ Customer ”) agrees that this Agreement governs Customer’s use of PandaDoc\nrestricted_uses:\n- summary: Free trial use limited to internal evaluation\n  text: such use is permitted only for Customer’s internal evaluation until the earlier\
  \ of\n- summary: Export control restrictions\n  text: Customer will not permit Users to access or use any Service, Documentation, or Customization in violation\n    of any applicable embargo restrictions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pandadoc/eligibility/pandadoc-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from PandaDoc's own page on 2026-11-10.
synthetic: false
tags:
- Document Automation
- E-Signature
- Document Management
- Document Generation
- Webhook
---
