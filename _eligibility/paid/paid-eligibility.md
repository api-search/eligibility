---
api_specs:
- filename: paid-agents-api-openapi.yml
  format: yaml
  label: Paid Agents API
  slug: paid-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paid/openapi/paid-agents-api-openapi.yml
- filename: paid-analyticsexperimental-api-openapi.yml
  format: yaml
  label: Paid Analytics Experimental API
  slug: paid-analyticsexperimental-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paid/openapi/paid-analyticsexperimental-api-openapi.yml
- filename: paid-checkouts-api-openapi.yml
  format: yaml
  label: Paid Checkouts API
  slug: paid-checkouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paid/openapi/paid-checkouts-api-openapi.yml
- filename: paid-contacts-api-openapi.yml
  format: yaml
  label: Paid Contacts API
  slug: paid-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paid/openapi/paid-contacts-api-openapi.yml
- filename: paid-costs-api-openapi.yml
  format: yaml
  label: Paid Costs API
  slug: paid-costs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paid/openapi/paid-costs-api-openapi.yml
- filename: paid-credits-api-openapi.yml
  format: yaml
  label: Paid Credits API
  slug: paid-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paid/openapi/paid-credits-api-openapi.yml
- filename: paid-customer-groups-api-openapi.yml
  format: yaml
  label: Paid Customer Groups API
  slug: paid-customer-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paid/openapi/paid-customer-groups-api-openapi.yml
- filename: paid-customer-portals-api-openapi.yml
  format: yaml
  label: Paid Customer Portals API
  slug: paid-customer-portals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paid/openapi/paid-customer-portals-api-openapi.yml
- filename: paid-customers-api-openapi.yml
  format: yaml
  label: Paid Customers API
  slug: paid-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paid/openapi/paid-customers-api-openapi.yml
- filename: paid-customviewsexperimental-api-openapi.yml
  format: yaml
  label: Paid Custom Views Experimental API
  slug: paid-customviewsexperimental-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paid/openapi/paid-customviewsexperimental-api-openapi.yml
- filename: paid-invoices-api-openapi.yml
  format: yaml
  label: Paid Invoices API
  slug: paid-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paid/openapi/paid-invoices-api-openapi.yml
- filename: paid-orders-api-openapi.yml
  format: yaml
  label: Paid Orders API
  slug: paid-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paid/openapi/paid-orders-api-openapi.yml
- filename: paid-orders-lines-api-openapi.yml
  format: yaml
  label: Paid orders > lines API
  slug: paid-orders-lines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paid/openapi/paid-orders-lines-api-openapi.yml
- filename: paid-plans-api-openapi.yml
  format: yaml
  label: Paid Plans API
  slug: paid-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paid/openapi/paid-plans-api-openapi.yml
- filename: paid-pricing-api-openapi.yml
  format: yaml
  label: Paid Pricing API
  slug: paid-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paid/openapi/paid-pricing-api-openapi.yml
- filename: paid-products-api-openapi.yml
  format: yaml
  label: Paid Products API
  slug: paid-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paid/openapi/paid-products-api-openapi.yml
- filename: paid-signals-api-openapi.yml
  format: yaml
  label: Paid Signals API
  slug: paid-signals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paid/openapi/paid-signals-api-openapi.yml
- filename: paid-traces-api-openapi.yml
  format: yaml
  label: Paid Traces API
  slug: paid-traces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paid/openapi/paid-traces-api-openapi.yml
- filename: paid-usage-api-openapi.yml
  format: yaml
  label: Paid Usage API
  slug: paid-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paid/openapi/paid-usage-api-openapi.yml
- filename: paid-value-models-api-openapi.yml
  format: yaml
  label: Paid Value Models API
  slug: paid-value-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paid/openapi/paid-value-models-api-openapi.yml
- filename: paid-value-receipts-api-openapi.yml
  format: yaml
  label: Paid Value Receipts API
  slug: paid-value-receipts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paid/openapi/paid-value-receipts-api-openapi.yml
- filename: paid-webhooks-api-openapi.yml
  format: yaml
  label: Paid Webhooks API
  slug: paid-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paid/openapi/paid-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Website is intended for business use only. By using the Website you confirm that you are acting on behalf of a business and not as a consumer.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Breach of law or others' rights
    text: use the Website in a way that breaches applicable law or infringes any person’s rights
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
name: Paid
provenance_date: '2026-11-10'
provider_name: Paid
provider_slug: paid
slug: paid-eligibility
source_date: '2026-11-10'
source_filename: paid-eligibility.yml
source_heading: Eligibility
source_page: https://paid.ai/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Paid\naid: paid\nurl: https://paid.ai/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Website is intended for business use only. By using the Website you confirm that you are acting on behalf\n    of a business and not as a consumer.\nrestricted_uses:\n- summary: Breach of law or others' rights\n  text: use the Website in a way that breaches applicable law or infringes any person’s rights\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/paid/eligibility/paid-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Paid's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Billing
- Monetization
- Payments
- Usage-Based Pricing
- AI Agents
- FinOps
---
