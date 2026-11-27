---
api_specs:
- filename: laserdata-account-api-openapi.yml
  format: yaml
  label: LaserData Account API
  slug: laserdata-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-account-api-openapi.yml
- filename: laserdata-api-keys-api-openapi.yml
  format: yaml
  label: LaserData API Keys API
  slug: laserdata-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-api-keys-api-openapi.yml
- filename: laserdata-audit-api-openapi.yml
  format: yaml
  label: LaserData Audit API
  slug: laserdata-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-audit-api-openapi.yml
- filename: laserdata-billing-api-openapi.yml
  format: yaml
  label: LaserData Billing API
  slug: laserdata-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-billing-api-openapi.yml
- filename: laserdata-cloud-accounts-api-openapi.yml
  format: yaml
  label: LaserData Cloud Accounts API
  slug: laserdata-cloud-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-cloud-accounts-api-openapi.yml
- filename: laserdata-clouds-api-openapi.yml
  format: yaml
  label: LaserData Clouds API
  slug: laserdata-clouds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-clouds-api-openapi.yml
- filename: laserdata-connectors-api-openapi.yml
  format: yaml
  label: LaserData Connectors API
  slug: laserdata-connectors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-connectors-api-openapi.yml
- filename: laserdata-deployments-api-openapi.yml
  format: yaml
  label: LaserData Deployments API
  slug: laserdata-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-deployments-api-openapi.yml
- filename: laserdata-divisions-api-openapi.yml
  format: yaml
  label: LaserData Divisions API
  slug: laserdata-divisions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-divisions-api-openapi.yml
- filename: laserdata-environments-api-openapi.yml
  format: yaml
  label: LaserData Environments API
  slug: laserdata-environments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-environments-api-openapi.yml
- filename: laserdata-invitations-api-openapi.yml
  format: yaml
  label: LaserData Invitations API
  slug: laserdata-invitations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-invitations-api-openapi.yml
- filename: laserdata-members-api-openapi.yml
  format: yaml
  label: LaserData Members API
  slug: laserdata-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-members-api-openapi.yml
- filename: laserdata-notification-channels-api-openapi.yml
  format: yaml
  label: LaserData Notification Channels API
  slug: laserdata-notification-channels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-notification-channels-api-openapi.yml
- filename: laserdata-notification-subscriptions-api-openapi.yml
  format: yaml
  label: LaserData Notification Subscriptions API
  slug: laserdata-notification-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-notification-subscriptions-api-openapi.yml
- filename: laserdata-notifications-api-openapi.yml
  format: yaml
  label: LaserData Notifications API
  slug: laserdata-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-notifications-api-openapi.yml
- filename: laserdata-payments-api-openapi.yml
  format: yaml
  label: LaserData Payments API
  slug: laserdata-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-payments-api-openapi.yml
- filename: laserdata-roles-api-openapi.yml
  format: yaml
  label: LaserData Roles API
  slug: laserdata-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-roles-api-openapi.yml
- filename: laserdata-tenants-api-openapi.yml
  format: yaml
  label: LaserData Tenants API
  slug: laserdata-tenants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-tenants-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not access or use the Services in embargoed countries or regions, by prohibited parties, or for prohibited end uses.
  entity_types:
  - text: The Services are intended for business and professional use.
    type: business
  minimum_age:
    text: You may use the Services only if you are at least 18 years old and legally able to enter into a binding agreement.
    value: '18'
  restricted_uses:
  - summary: Highly Regulated Data
    text: Unless expressly authorized in a written agreement with LaserData, you may not use the Services to process protected health information subject to HIPAA, payment card data or cardholder data subject to PCI DSS except payment information submitted directly to our payment processor for LaserData billing
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
name: LaserData
provenance_date: '2026-11-09'
provider_name: LaserData
provider_slug: laserdata
slug: laserdata-eligibility
source_date: '2026-11-09'
source_filename: laserdata-eligibility.yml
source_heading: Eligibility
source_page: https://laserdata.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LaserData\naid: laserdata\nurl: https://laserdata.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not access or use the Services in embargoed countries or regions, by prohibited parties, or for\n    prohibited end uses.\nentity_types:\n- type: business\n  text: The Services are intended for business and professional use.\nrestricted_uses:\n- summary: Highly Regulated Data\n  text: Unless expressly authorized in a written agreement with LaserData, you may not use the Services to process\n    protected health information subject to HIPAA, payment card data or cardholder\
  \ data subject to PCI DSS except\n    payment information submitted directly to our payment processor for LaserData billing\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may use the Services only if you are at least 18 years old and legally able to enter into a binding\n    agreement.\n"
source_yaml_url: https://artifacts.apis.io/laserdata/eligibility/laserdata-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from LaserData's own page on 2026-11-09.
synthetic: false
tags:
- Streaming
- Message Streaming
- Event Streaming
- Data Infrastructure
- Real-Time
- Apache Iggy
- Rust
- Cloud Infrastructure
- AI Agents
- Observability
- Company
---
