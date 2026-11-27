---
api_specs:
- filename: total-expert-account-endpoints-api-openapi.yml
  format: yaml
  label: Total Expert Account Endpoints API
  slug: total-expert-account-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/total-expert/openapi/total-expert-account-endpoints-api-openapi.yml
- filename: total-expert-activity-endpoints-api-openapi.yml
  format: yaml
  label: Total Expert Activity Endpoints API
  slug: total-expert-activity-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/total-expert/openapi/total-expert-activity-endpoints-api-openapi.yml
- filename: total-expert-alm-leads-formerly-lead-opportunities-api-openapi.yml
  format: yaml
  label: Total Expert ALM Leads (formerly Lead Opportunities) API
  slug: total-expert-alm-leads-formerly-lead-opportunities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/total-expert/openapi/total-expert-alm-leads-formerly-lead-opportunities-api-openapi.yml
- filename: total-expert-authentication-api-openapi.yml
  format: yaml
  label: Total Expert Authentication API
  slug: total-expert-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/total-expert/openapi/total-expert-authentication-api-openapi.yml
- filename: total-expert-contact-endpoints-api-openapi.yml
  format: yaml
  label: Total Expert Contact Endpoints API
  slug: total-expert-contact-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/total-expert/openapi/total-expert-contact-endpoints-api-openapi.yml
- filename: total-expert-email-apis-api-openapi.yml
  format: yaml
  label: Total Expert Email APIs API
  slug: total-expert-email-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/total-expert/openapi/total-expert-email-apis-api-openapi.yml
- filename: total-expert-email-unsubscribes-api-openapi.yml
  format: yaml
  label: Total Expert Email Unsubscribes API
  slug: total-expert-email-unsubscribes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/total-expert/openapi/total-expert-email-unsubscribes-api-openapi.yml
- filename: total-expert-entities-api-openapi.yml
  format: yaml
  label: Total Expert Entities API
  slug: total-expert-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/total-expert/openapi/total-expert-entities-api-openapi.yml
- filename: total-expert-heartbeat-api-openapi.yml
  format: yaml
  label: Total Expert Heartbeat API
  slug: total-expert-heartbeat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/total-expert/openapi/total-expert-heartbeat-api-openapi.yml
- filename: total-expert-insight-endpoints-api-openapi.yml
  format: yaml
  label: Total Expert Insight Endpoints API
  slug: total-expert-insight-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/total-expert/openapi/total-expert-insight-endpoints-api-openapi.yml
- filename: total-expert-lead-opportunities-new-api-openapi.yml
  format: yaml
  label: Total Expert Lead Opportunities (New) API
  slug: total-expert-lead-opportunities-new-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/total-expert/openapi/total-expert-lead-opportunities-new-api-openapi.yml
- filename: total-expert-loan-endpoints-api-openapi.yml
  format: yaml
  label: Total Expert Loan Endpoints API
  slug: total-expert-loan-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/total-expert/openapi/total-expert-loan-endpoints-api-openapi.yml
- filename: total-expert-scenarios-api-openapi.yml
  format: yaml
  label: Total Expert Scenarios API
  slug: total-expert-scenarios-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/total-expert/openapi/total-expert-scenarios-api-openapi.yml
- filename: total-expert-schema-endpoints-api-openapi.yml
  format: yaml
  label: Total Expert Schema Endpoints API
  slug: total-expert-schema-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/total-expert/openapi/total-expert-schema-endpoints-api-openapi.yml
- filename: total-expert-sms-opting-api-openapi.yml
  format: yaml
  label: Total Expert SMS Opting API
  slug: total-expert-sms-opting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/total-expert/openapi/total-expert-sms-opting-api-openapi.yml
- filename: total-expert-user-endpoints-api-openapi.yml
  format: yaml
  label: Total Expert User Endpoints API
  slug: total-expert-user-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/total-expert/openapi/total-expert-user-endpoints-api-openapi.yml
- filename: total-expert-webhooks-api-openapi.yml
  format: yaml
  label: Total Expert Webhooks API
  slug: total-expert-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/total-expert/openapi/total-expert-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: not barred from receiving services under the laws of the United States or other applicable jurisdiction.
  entity_types:
  - text: Each Subscription is a single product, for an individual user, or group of users for Multiple User Subscriptions.
    type: individual
  minimum_age:
    text: provided that you are of legal age to form a binding contract
    value: legal age to form a binding contract
  restricted_uses:
  - summary: Disallowed data types
    text: 'You represent and warrant that you will not, and will not permit any user to, enter or upload into the Software or any other Service any of the following data types: (a) financial account or payment card information, (b) patient, medical, or other protected health information'
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
name: Total Expert
provenance_date: '2026-11-10'
provider_name: Total Expert
provider_slug: total-expert
slug: total-expert-eligibility
source_date: '2026-11-10'
source_filename: total-expert-eligibility.yml
source_heading: Eligibility
source_page: https://www.totalexpert.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Total Expert\naid: total-expert\nurl: https://www.totalexpert.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: not barred from receiving services under the laws of the United States or other applicable jurisdiction.\nentity_types:\n- type: individual\n  text: Each Subscription is a single product, for an individual user, or group of users for Multiple User Subscriptions.\nrestricted_uses:\n- summary: Disallowed data types\n  text: 'You represent and warrant that you will not, and will not permit any user to, enter or upload into the\n    Software or any other\
  \ Service any of the following data types: (a) financial account or payment card information,\n    (b) patient, medical, or other protected health information'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age to form a binding contract\n  text: provided that you are of legal age to form a binding contract\n"
source_yaml_url: https://artifacts.apis.io/total-expert/eligibility/total-expert-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Total Expert's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- CRM
- Marketing Automation
- Mortgage
- Banking
- Lending
- Customer Engagement
---
