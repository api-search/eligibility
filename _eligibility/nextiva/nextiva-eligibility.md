---
api_specs:
- filename: nextiva-authentication-api-openapi.yml
  format: yaml
  label: Nextiva Authentication API
  slug: nextiva-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nextiva/openapi/nextiva-authentication-api-openapi.yml
- filename: nextiva-call-management-api-openapi.yml
  format: yaml
  label: Nextiva Call Management API
  slug: nextiva-call-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nextiva/openapi/nextiva-call-management-api-openapi.yml
- filename: nextiva-campaigns-api-openapi.yml
  format: yaml
  label: Nextiva Campaigns API
  slug: nextiva-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nextiva/openapi/nextiva-campaigns-api-openapi.yml
- filename: nextiva-conversations-api-openapi.yml
  format: yaml
  label: Nextiva Conversations API
  slug: nextiva-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nextiva/openapi/nextiva-conversations-api-openapi.yml
- filename: nextiva-dtmf-api-openapi.yml
  format: yaml
  label: Nextiva DTMF API
  slug: nextiva-dtmf-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nextiva/openapi/nextiva-dtmf-api-openapi.yml
- filename: nextiva-email-api-openapi.yml
  format: yaml
  label: Nextiva Email API
  slug: nextiva-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nextiva/openapi/nextiva-email-api-openapi.yml
- filename: nextiva-sms-messaging-api-openapi.yml
  format: yaml
  label: Nextiva SMS Messaging API
  slug: nextiva-sms-messaging-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nextiva/openapi/nextiva-sms-messaging-api-openapi.yml
- filename: nextiva-tickets-api-openapi.yml
  format: yaml
  label: Nextiva Tickets API
  slug: nextiva-tickets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nextiva/openapi/nextiva-tickets-api-openapi.yml
- filename: nextiva-transfers-api-openapi.yml
  format: yaml
  label: Nextiva Transfers API
  slug: nextiva-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nextiva/openapi/nextiva-transfers-api-openapi.yml
- filename: nextiva-work-items-api-openapi.yml
  format: yaml
  label: Nextiva Work Items API
  slug: nextiva-work-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nextiva/openapi/nextiva-work-items-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Nextiva does not presently offer or support the Services to customers located in any countries other than the United States except where expressly agreed by Nextiva in writing.
  entity_types:
  - text: Services are provided to you as a business user, for your business and home office use.
    type: business
  minimum_age:
    text: You represent and warrant that you are at least eighteen (18) years of age or, as applicable, the age of majority in the country, state or province in which you reside
    value: '18'
  restricted_uses:
  - summary: No personal or nonbusiness use
    text: you are not using it for any personal, residential, nonbusiness and nonprofessional purpose
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: All Services provided to You and covered by the Agreement shall at all times be subject to credit approval or review by Nextiva.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Nextiva
provenance_date: '2026-11-10'
provider_name: Nextiva
provider_slug: nextiva
slug: nextiva-eligibility
source_date: '2026-11-10'
source_filename: nextiva-eligibility.yml
source_heading: Eligibility
source_page: https://www.nextiva.com/legal.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nextiva\naid: nextiva\nurl: https://www.nextiva.com/legal.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Nextiva does not presently offer or support the Services to customers located in any countries other than\n    the United States except where expressly agreed by Nextiva in writing.\nentity_types:\n- type: business\n  text: Services are provided to you as a business user, for your business and home office use.\nrestricted_uses:\n- summary: No personal or nonbusiness use\n  text: you are not using it for any personal, residential, nonbusiness and nonprofessional\
  \ purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: All Services provided to You and covered by the Agreement shall at all times be subject to credit approval\n    or review by Nextiva.\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are at least eighteen (18) years of age or, as applicable, the age of\n    majority in the country, state or province in which you reside\n"
source_yaml_url: https://artifacts.apis.io/nextiva/eligibility/nextiva-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Nextiva's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Communications
- Voice
- Contact Center
- Customer Experience
- SMS
- Messaging
- Unified Communications
- VoIP
- Telephony
- Conversational AI
- Call Center
---
