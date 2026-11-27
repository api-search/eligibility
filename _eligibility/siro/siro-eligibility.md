---
api_specs:
- filename: siro-audit-api-openapi.yml
  format: yaml
  label: Siro Audit API
  slug: siro-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siro/openapi/siro-audit-api-openapi.yml
- filename: siro-core-api-openapi.yml
  format: yaml
  label: Siro Core API
  slug: siro-core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siro/openapi/siro-core-api-openapi.yml
- filename: siro-folders-api-openapi.yml
  format: yaml
  label: Siro Folders API
  slug: siro-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siro/openapi/siro-folders-api-openapi.yml
- filename: siro-integrations-api-openapi.yml
  format: yaml
  label: Siro Integrations API
  slug: siro-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siro/openapi/siro-integrations-api-openapi.yml
- filename: siro-agents-api-openapi.yml
  format: yaml
  label: Siro Agents API
  slug: siro-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siro/openapi/siro-agents-api-openapi.yml
- filename: siro-billing-graph-api-openapi.yml
  format: yaml
  label: Siro Billing Graph API
  slug: siro-billing-graph-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siro/openapi/siro-billing-graph-api-openapi.yml
- filename: siro-docs-api-openapi.yml
  format: yaml
  label: Siro Docs API
  slug: siro-docs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siro/openapi/siro-docs-api-openapi.yml
- filename: siro-halftime-api-openapi.yml
  format: yaml
  label: Siro Halftime API
  slug: siro-halftime-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siro/openapi/siro-halftime-api-openapi.yml
- filename: siro-intercom-api-openapi.yml
  format: yaml
  label: Siro Intercom API
  slug: siro-intercom-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siro/openapi/siro-intercom-api-openapi.yml
- filename: siro-invoices-api-openapi.yml
  format: yaml
  label: Siro Invoices API
  slug: siro-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siro/openapi/siro-invoices-api-openapi.yml
- filename: siro-jobs-api-openapi.yml
  format: yaml
  label: Siro Jobs API
  slug: siro-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siro/openapi/siro-jobs-api-openapi.yml
- filename: siro-licenses-api-openapi.yml
  format: yaml
  label: Siro Licenses API
  slug: siro-licenses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siro/openapi/siro-licenses-api-openapi.yml
- filename: siro-portal-api-openapi.yml
  format: yaml
  label: Siro Portal API
  slug: siro-portal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siro/openapi/siro-portal-api-openapi.yml
- filename: siro-sessions-api-openapi.yml
  format: yaml
  label: Siro Sessions API
  slug: siro-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siro/openapi/siro-sessions-api-openapi.yml
- filename: siro-subscription-api-openapi.yml
  format: yaml
  label: Siro Subscription API
  slug: siro-subscription-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siro/openapi/siro-subscription-api-openapi.yml
- filename: siro-suggested-questions-api-openapi.yml
  format: yaml
  label: Siro Suggested Questions API
  slug: siro-suggested-questions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siro/openapi/siro-suggested-questions-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use only for Subscriber's business purposes
    text: solely for Subscriber’s business purposes during the Subscription Term
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
name: Siro
provenance_date: '2026-11-10'
provider_name: Siro
provider_slug: siro
slug: siro-eligibility
source_date: '2026-11-10'
source_filename: siro-eligibility.yml
source_heading: Eligibility
source_page: https://www.siro.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Siro\naid: siro\nurl: https://www.siro.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Use only for Subscriber's business purposes\n  text: solely for Subscriber’s business purposes during the Subscription Term\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/siro/eligibility/siro-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Siro's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sales
- Sales Coaching
- Conversation Intelligence
- Field Sales
- CRM
- Artificial Intelligence
- Speech-to-Text
- Webhook
- Integration
- A2A
---
