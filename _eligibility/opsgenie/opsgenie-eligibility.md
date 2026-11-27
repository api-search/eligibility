---
api_specs:
- filename: opsgenie-account-api-openapi.yml
  format: yaml
  label: OpsGenie Account API
  slug: opsgenie-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opsgenie/openapi/opsgenie-account-api-openapi.yml
- filename: opsgenie-alerts-api-openapi.yml
  format: yaml
  label: OpsGenie Alerts API
  slug: opsgenie-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opsgenie/openapi/opsgenie-alerts-api-openapi.yml
- filename: opsgenie-escalations-api-openapi.yml
  format: yaml
  label: OpsGenie Escalations API
  slug: opsgenie-escalations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opsgenie/openapi/opsgenie-escalations-api-openapi.yml
- filename: opsgenie-heartbeats-api-openapi.yml
  format: yaml
  label: OpsGenie Heartbeats API
  slug: opsgenie-heartbeats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opsgenie/openapi/opsgenie-heartbeats-api-openapi.yml
- filename: opsgenie-incidents-api-openapi.yml
  format: yaml
  label: OpsGenie Incidents API
  slug: opsgenie-incidents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opsgenie/openapi/opsgenie-incidents-api-openapi.yml
- filename: opsgenie-integrations-api-openapi.yml
  format: yaml
  label: OpsGenie Integrations API
  slug: opsgenie-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opsgenie/openapi/opsgenie-integrations-api-openapi.yml
- filename: opsgenie-maintenance-api-openapi.yml
  format: yaml
  label: OpsGenie Maintenance API
  slug: opsgenie-maintenance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opsgenie/openapi/opsgenie-maintenance-api-openapi.yml
- filename: opsgenie-notification-rules-api-openapi.yml
  format: yaml
  label: OpsGenie Notification Rules API
  slug: opsgenie-notification-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opsgenie/openapi/opsgenie-notification-rules-api-openapi.yml
- filename: opsgenie-on-call-api-openapi.yml
  format: yaml
  label: OpsGenie On-Call API
  slug: opsgenie-on-call-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opsgenie/openapi/opsgenie-on-call-api-openapi.yml
- filename: opsgenie-overrides-api-openapi.yml
  format: yaml
  label: OpsGenie Overrides API
  slug: opsgenie-overrides-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opsgenie/openapi/opsgenie-overrides-api-openapi.yml
- filename: opsgenie-rotations-api-openapi.yml
  format: yaml
  label: OpsGenie Rotations API
  slug: opsgenie-rotations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opsgenie/openapi/opsgenie-rotations-api-openapi.yml
- filename: opsgenie-schedules-api-openapi.yml
  format: yaml
  label: OpsGenie Schedules API
  slug: opsgenie-schedules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opsgenie/openapi/opsgenie-schedules-api-openapi.yml
- filename: opsgenie-services-api-openapi.yml
  format: yaml
  label: OpsGenie Services API
  slug: opsgenie-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opsgenie/openapi/opsgenie-services-api-openapi.yml
- filename: opsgenie-teams-api-openapi.yml
  format: yaml
  label: OpsGenie Teams API
  slug: opsgenie-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opsgenie/openapi/opsgenie-teams-api-openapi.yml
- filename: opsgenie-users-api-openapi.yml
  format: yaml
  label: OpsGenie Users API
  slug: opsgenie-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opsgenie/openapi/opsgenie-users-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'If you (the person accepting this Agreement) are accepting this Agreement on behalf of your employer or another entity, you agree that: (i) you have full legal authority to bind your employer or such entity to this Agreement'
    type: business
  - text: If Customer is a United States federal, state or local government customer, this Agreement is subject to, and is varied by, the Government Amendment
    type: government
  minimum_age:
    text: The Products are not intended for use by anyone under the age of 16.
    value: '16'
  restricted_uses:
  - summary: No unprotected health information
    text: Customer must not (and must not permit anyone else to) upload to the Cloud Products (or use the Cloud Products to process) any patient, medical or other protected health information regulated by the Health Insurance Portability and Accountability Act.
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
name: OpsGenie
provenance_date: '2026-11-10'
provider_name: OpsGenie
provider_slug: opsgenie
slug: opsgenie-eligibility
source_date: '2026-11-10'
source_filename: opsgenie-eligibility.yml
source_heading: Eligibility
source_page: https://www.atlassian.com/legal/atlassian-customer-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OpsGenie\naid: opsgenie\nurl: https://www.atlassian.com/legal/atlassian-customer-agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'If you (the person accepting this Agreement) are accepting this Agreement on behalf of your employer or\n    another entity, you agree that: (i) you have full legal authority to bind your employer or such entity to this\n    Agreement'\n- type: government\n  text: If Customer is a United States federal, state or local government customer, this Agreement is subject to,\n    and is varied by, the Government\
  \ Amendment\nrestricted_uses:\n- summary: No unprotected health information\n  text: Customer must not (and must not permit anyone else to) upload to the Cloud Products (or use the Cloud Products\n    to process) any patient, medical or other protected health information regulated by the Health Insurance Portability\n    and Accountability Act.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: The Products are not intended for use by anyone under the age of 16.\n"
source_yaml_url: https://artifacts.apis.io/opsgenie/eligibility/opsgenie-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from OpsGenie's own page on 2026-11-10.
synthetic: false
tags:
- Alerts
- Incident Management
- Monitoring
- On-Call
- Incident Response
---
