---
api_specs:
- filename: ada-channels-api-openapi.yml
  format: yaml
  label: Ada Channels API
  slug: ada-channels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ada/openapi/ada-channels-api-openapi.yml
- filename: ada-conversations-api-openapi.yml
  format: yaml
  label: Ada Conversations API
  slug: ada-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ada/openapi/ada-conversations-api-openapi.yml
- filename: ada-custominstructions-api-openapi.yml
  format: yaml
  label: Ada Custom Instructions API
  slug: ada-custominstructions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ada/openapi/ada-custominstructions-api-openapi.yml
- filename: ada-deletechatterdata-api-openapi.yml
  format: yaml
  label: Ada Delete Chatter Data API
  slug: ada-deletechatterdata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ada/openapi/ada-deletechatterdata-api-openapi.yml
- filename: ada-getdeletionjob-api-openapi.yml
  format: yaml
  label: Ada Get Deletion Job API
  slug: ada-getdeletionjob-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ada/openapi/ada-getdeletionjob-api-openapi.yml
- filename: ada-knowledge-api-openapi.yml
  format: yaml
  label: Ada Knowledge API
  slug: ada-knowledge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ada/openapi/ada-knowledge-api-openapi.yml
- filename: ada-knowledge-articles-api-openapi.yml
  format: yaml
  label: Ada knowledge > articles API
  slug: ada-knowledge-articles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ada/openapi/ada-knowledge-articles-api-openapi.yml
- filename: ada-knowledge-sources-api-openapi.yml
  format: yaml
  label: Ada knowledge > sources API
  slug: ada-knowledge-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ada/openapi/ada-knowledge-sources-api-openapi.yml
- filename: ada-knowledge-tags-api-openapi.yml
  format: yaml
  label: Ada knowledge > tags API
  slug: ada-knowledge-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ada/openapi/ada-knowledge-tags-api-openapi.yml
- filename: ada-messages-api-openapi.yml
  format: yaml
  label: Ada Messages API
  slug: ada-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ada/openapi/ada-messages-api-openapi.yml
- filename: ada-persona-api-openapi.yml
  format: yaml
  label: Ada Persona API
  slug: ada-persona-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ada/openapi/ada-persona-api-openapi.yml
- filename: ada-platformintegrations-api-openapi.yml
  format: yaml
  label: Ada Platform Integrations API
  slug: ada-platformintegrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ada/openapi/ada-platformintegrations-api-openapi.yml
- filename: ada-submitdeletionrequest-api-openapi.yml
  format: yaml
  label: Ada Submit Deletion Request API
  slug: ada-submitdeletionrequest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ada/openapi/ada-submitdeletionrequest-api-openapi.yml
- filename: ada-variables-api-openapi.yml
  format: yaml
  label: Ada Variables API
  slug: ada-variables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ada/openapi/ada-variables-api-openapi.yml
- filename: ada-audit-log-api-openapi.yml
  format: yaml
  label: Ada Audit Log API
  slug: ada-audit-log-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ada/openapi/ada-audit-log-api-openapi.yml
- filename: ada-end-users-api-openapi.yml
  format: yaml
  label: Ada End Users API
  slug: ada-end-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ada/openapi/ada-end-users-api-openapi.yml
- filename: ada-webhook-management-api-openapi.yml
  format: yaml
  label: Ada Webhook Management API
  slug: ada-webhook-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ada/openapi/ada-webhook-management-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'Each Party represents and warrants to the other Party that: it is a corporation, duly organized, validly existing and in good standing under the laws of its jurisdiction of incorporation'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No personal health information except under BAA
    text: not use the Services to transmit, store, or process personal health information, including health information subject to United States Health Insurance Portability and Accountability Act (“HIPAA”) regulations except as permitted by an executed HIPAA Business Associate Agreement.
  - summary: No sensitive payment data
    text: not request any sensitive Personal Information, including credit card or banking information, from its End Users through the Services
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
name: Ada
provenance_date: '2026-11-09'
provider_name: Ada
provider_slug: ada
slug: ada-eligibility
source_date: '2026-11-09'
source_filename: ada-eligibility.yml
source_heading: Eligibility
source_page: https://www.ada.cx/legal/customer-terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ada\naid: ada\nurl: https://www.ada.cx/legal/customer-terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'Each Party represents and warrants to the other Party that: it is a corporation, duly organized, validly\n    existing and in good standing under the laws of its jurisdiction of incorporation'\nrestricted_uses:\n- summary: No personal health information except under BAA\n  text: not use the Services to transmit, store, or process personal health information, including health information\n    subject to United States Health\
  \ Insurance Portability and Accountability Act (“HIPAA”) regulations except as\n    permitted by an executed HIPAA Business Associate Agreement.\n- summary: No sensitive payment data\n  text: not request any sensitive Personal Information, including credit card or banking information, from its End\n    Users through the Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ada/eligibility/ada-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Ada's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Customer Service
- Chatbots
- Automation
- Conversational AI
- Help Desk
- CRM
- Integration
- Knowledge Management
- Data Export
- Canada
---
