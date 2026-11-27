---
api_specs:
- filename: filevine-identity-api-openapi.yml
  format: yaml
  label: Filevine Identity API
  slug: filevine-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filevine/openapi/filevine-identity-api-openapi.yml
- filename: filevine-projects-api-openapi.yml
  format: yaml
  label: Filevine Projects API
  slug: filevine-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filevine/openapi/filevine-projects-api-openapi.yml
- filename: filevine-contacts-api-openapi.yml
  format: yaml
  label: Filevine Contacts API
  slug: filevine-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filevine/openapi/filevine-contacts-api-openapi.yml
- filename: filevine-documents-api-openapi.yml
  format: yaml
  label: Filevine Documents API
  slug: filevine-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filevine/openapi/filevine-documents-api-openapi.yml
- filename: filevine-notes-api-openapi.yml
  format: yaml
  label: Filevine Notes API
  slug: filevine-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filevine/openapi/filevine-notes-api-openapi.yml
- filename: filevine-deadlines-api-openapi.yml
  format: yaml
  label: Filevine Deadlines API
  slug: filevine-deadlines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filevine/openapi/filevine-deadlines-api-openapi.yml
- filename: filevine-tasks-api-openapi.yml
  format: yaml
  label: Filevine Tasks API
  slug: filevine-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filevine/openapi/filevine-tasks-api-openapi.yml
- filename: filevine-webhooks-api-openapi.yml
  format: yaml
  label: Filevine Webhooks API
  slug: filevine-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filevine/openapi/filevine-webhooks-api-openapi.yml
- filename: filevine-time-entries-api-openapi.yml
  format: yaml
  label: Filevine Time Entries API
  slug: filevine-time-entries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filevine/openapi/filevine-time-entries-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are operated by us in the United States. Those who choose to access the Services from locations outside the United States do so at their own initiative and are responsible for compliance with applicable local laws.
  minimum_age:
    text: You must be 18 years of age or older to use the Services.
    value: '18'
  restricted_uses:
  - summary: Free access is business use only
    text: A Free Access Subscriptions is only intended for business use, personal use is prohibited.
  - summary: No use by competitors
    text: use the Services if you are directly or indirectly a competitor of the Company
  - source: https://www.filevine.com/legal/subscription-agreement/
    summary: Competitors of Filevine
    text: use the Services if Subscriber or any Authorized User is a competitor of Filevine (including a company whose primary business is developing and commercially offering AI-powered legal practice management or case management software products competitive with the Services)
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you will be required to provide a valid business email in order to sign up for a Free Access Subscription.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Filevine
provenance_date: '2026-11-09'
provider_name: Filevine
provider_slug: filevine
slug: filevine-eligibility
source_date: '2026-11-09'
source_filename: filevine-eligibility.yml
source_heading: Eligibility
source_page: https://www.filevine.com/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Filevine\naid: filevine\nurl: https://www.filevine.com/legal/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.filevine.com/legal/subscription-agreement/\n  - https://www.filevine.com/legal/terms-of-service/\ncountries:\n  served: []\n  excluded: []\n  text: The Services are operated by us in the United States. Those who choose to access the Services from locations\n    outside the United States do so at their own initiative and are responsible for compliance with applicable local\n    laws.\nentity_types: []\nrestricted_uses:\n- summary: Free access is business use only\n  text: A Free\
  \ Access Subscriptions is only intended for business use, personal use is prohibited.\n- summary: No use by competitors\n  text: use the Services if you are directly or indirectly a competitor of the Company\n- summary: Competitors of Filevine\n  text: use the Services if Subscriber or any Authorized User is a competitor of Filevine (including a company whose\n    primary business is developing and commercially offering AI-powered legal practice management or case management\n    software products competitive with the Services)\n  source: https://www.filevine.com/legal/subscription-agreement/\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you will be required to provide a valid business email in order to sign up for a Free Access Subscription.\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/filevine/eligibility/filevine-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Filevine's own page on 2026-11-09.
synthetic: false
tags:
- Legal
- Case Management
- Matter
- Intake
- Documents
- LOIS
- Webhook
- Legal AI
- Personal Injury
- Mass Torts
---
