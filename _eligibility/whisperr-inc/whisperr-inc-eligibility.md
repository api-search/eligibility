---
api_specs:
- filename: whisperr-inc-dashboard-api-openapi.yml
  format: yaml
  label: Whisperr, Inc. Dashboard API
  slug: whisperr-inc-dashboard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whisperr-inc/openapi/whisperr-inc-dashboard-api-openapi.yml
- filename: whisperr-inc-decisioning-api-openapi.yml
  format: yaml
  label: Whisperr, Inc. Decisioning API
  slug: whisperr-inc-decisioning-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whisperr-inc/openapi/whisperr-inc-decisioning-api-openapi.yml
- filename: whisperr-inc-delivery-api-openapi.yml
  format: yaml
  label: Whisperr, Inc. Delivery API
  slug: whisperr-inc-delivery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whisperr-inc/openapi/whisperr-inc-delivery-api-openapi.yml
- filename: whisperr-inc-ingestion-api-openapi.yml
  format: yaml
  label: Whisperr, Inc. Ingestion API
  slug: whisperr-inc-ingestion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whisperr-inc/openapi/whisperr-inc-ingestion-api-openapi.yml
- filename: whisperr-inc-internal-api-openapi.yml
  format: yaml
  label: Whisperr, Inc. Internal API
  slug: whisperr-inc-internal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whisperr-inc/openapi/whisperr-inc-internal-api-openapi.yml
- filename: whisperr-inc-system-api-openapi.yml
  format: yaml
  label: Whisperr, Inc. System API
  slug: whisperr-inc-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whisperr-inc/openapi/whisperr-inc-system-api-openapi.yml
- filename: whisperr-inc-users-api-openapi.yml
  format: yaml
  label: Whisperr, Inc. Users API
  slug: whisperr-inc-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whisperr-inc/openapi/whisperr-inc-users-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that You are not located in, organized under the laws of, or ordinarily resident in a country or territory subject to comprehensive sanctions
  entity_types:
  - text: The Platform is offered for business and professional use. It is not directed to consumers and is not intended for personal, family, or household purposes.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sensitive data and children's data
    text: send special categories of personal data, government identifiers, payment card numbers, passwords, or data of children through the Platform unless expressly agreed in writing with Whisperr
  - summary: Legally significant decisions
    text: You will not use it to make decisions that have legal or similarly significant effects on End Users.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To register, You provide accurate Account information and keep it current.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Whisperr
provenance_date: '2026-11-10'
provider_name: Whisperr
provider_slug: whisperr-inc
slug: whisperr-inc-eligibility
source_date: '2026-11-10'
source_filename: whisperr-inc-eligibility.yml
source_heading: Eligibility
source_page: https://whisperr.net/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Whisperr\naid: whisperr-inc\nurl: https://whisperr.net/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that You are not located in, organized under the laws of, or ordinarily resident in a country\n    or territory subject to comprehensive sanctions\nentity_types:\n- type: business\n  text: The Platform is offered for business and professional use. It is not directed to consumers and is not intended\n    for personal, family, or household purposes.\nrestricted_uses:\n- summary: Sensitive data and children's data\n  text: send special categories of personal data,\
  \ government identifiers, payment card numbers, passwords, or data\n    of children through the Platform unless expressly agreed in writing with Whisperr\n- summary: Legally significant decisions\n  text: You will not use it to make decisions that have legal or similarly significant effects on End Users.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To register, You provide accurate Account information and keep it current.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/whisperr-inc/eligibility/whisperr-inc-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Whisperr's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Customer Retention
- Churn
- Marketing Automation
- Artificial Intelligence
- Software-as-a-Service
- Subscription
- Customer Engagement
- Event Ingestion
- Analytics
- Customer Data
- Email Delivery
- Agents
---
