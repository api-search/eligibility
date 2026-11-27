---
api_specs:
- filename: quo-calls-api-openapi.yml
  format: yaml
  label: Quo Calls API
  slug: quo-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quo/openapi/quo-calls-api-openapi.yml
- filename: quo-contact-custom-fields-api-openapi.yml
  format: yaml
  label: Quo Contact Custom Fields API
  slug: quo-contact-custom-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quo/openapi/quo-contact-custom-fields-api-openapi.yml
- filename: quo-contacts-api-openapi.yml
  format: yaml
  label: Quo Contacts API
  slug: quo-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quo/openapi/quo-contacts-api-openapi.yml
- filename: quo-conversations-api-openapi.yml
  format: yaml
  label: Quo Conversations API
  slug: quo-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quo/openapi/quo-conversations-api-openapi.yml
- filename: quo-messages-api-openapi.yml
  format: yaml
  label: Quo Messages API
  slug: quo-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quo/openapi/quo-messages-api-openapi.yml
- filename: quo-phone-numbers-api-openapi.yml
  format: yaml
  label: Quo Phone Numbers API
  slug: quo-phone-numbers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quo/openapi/quo-phone-numbers-api-openapi.yml
- filename: quo-tasks-api-openapi.yml
  format: yaml
  label: Quo Tasks API
  slug: quo-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quo/openapi/quo-tasks-api-openapi.yml
- filename: quo-users-api-openapi.yml
  format: yaml
  label: Quo Users API
  slug: quo-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quo/openapi/quo-users-api-openapi.yml
- filename: quo-webhooks-api-openapi.yml
  format: yaml
  label: Quo Webhooks API
  slug: quo-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quo/openapi/quo-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this Agreement on behalf of an entity, then you represent and warrant that you are authorized to bind such entity to the terms of this Agreement.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export and sanctions
    text: Developer agrees that it shall not permit the use of the Service or API or OpenPhone Data, export, or re-export the Service or API or OpenPhone Data
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Prior to accessing the API or developing an Integration, Developer shall complete OpenPhone’s standard registration process
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Quo
provenance_date: '2026-11-10'
provider_name: Quo
provider_slug: quo
slug: quo-eligibility
source_date: '2026-11-10'
source_filename: quo-eligibility.yml
source_heading: Eligibility
source_page: https://www.quo.com/docs/mdx/pricing-support/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Quo\naid: quo\nurl: https://www.quo.com/docs/mdx/pricing-support/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this Agreement on behalf of an entity, then you represent and warrant that you\n    are authorized to bind such entity to the terms of this Agreement.\nrestricted_uses:\n- summary: Export and sanctions\n  text: Developer agrees that it shall not permit the use of the Service or API or OpenPhone Data, export, or re-export\n    the Service or API or OpenPhone Data\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: Prior to accessing the API or developing an Integration, Developer shall complete OpenPhone’s standard registration\n    process\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/quo/eligibility/quo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Quo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Communications
- Messaging
- SMS
- Voice
- Contacts
- Webhook
- Telephony
- Business Phone
- CPaaS
- Contact Center
- Phone System
- Shared Numbers
- AI Agents
- Small Business
- Integration
- CRM
- Call Routing
---
