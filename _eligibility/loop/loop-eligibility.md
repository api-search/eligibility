---
api_specs:
- filename: loop-artifacts-api-openapi.yml
  format: yaml
  label: Loop Artifacts API
  slug: loop-artifacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loop/openapi/loop-artifacts-api-openapi.yml
- filename: loop-artifacts-schema-validated-api-openapi.yml
  format: yaml
  label: Loop Artifacts Schema Validated API
  slug: loop-artifacts-schema-validated-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loop/openapi/loop-artifacts-schema-validated-api-openapi.yml
- filename: loop-business-exceptions-api-openapi.yml
  format: yaml
  label: Loop Business Exceptions API
  slug: loop-business-exceptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loop/openapi/loop-business-exceptions-api-openapi.yml
- filename: loop-factoring-relationships-api-openapi.yml
  format: yaml
  label: Loop Factoring Relationships API
  slug: loop-factoring-relationships-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loop/openapi/loop-factoring-relationships-api-openapi.yml
- filename: loop-invoicing-relationships-api-openapi.yml
  format: yaml
  label: Loop Invoicing Relationships API
  slug: loop-invoicing-relationships-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loop/openapi/loop-invoicing-relationships-api-openapi.yml
- filename: loop-onboarding-api-loop-com-api-openapi.yml
  format: yaml
  label: Loop Onboarding.api.loop.com API
  slug: loop-onboarding-api-loop-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loop/openapi/loop-onboarding-api-loop-com-api-openapi.yml
- filename: loop-organizations-api-openapi.yml
  format: yaml
  label: Loop Organizations API
  slug: loop-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loop/openapi/loop-organizations-api-openapi.yml
- filename: loop-payable-allocations-api-openapi.yml
  format: yaml
  label: Loop Payable Allocations API
  slug: loop-payable-allocations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loop/openapi/loop-payable-allocations-api-openapi.yml
- filename: loop-payable-invoice-reviews-api-openapi.yml
  format: yaml
  label: Loop Payable Invoice Reviews API
  slug: loop-payable-invoice-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loop/openapi/loop-payable-invoice-reviews-api-openapi.yml
- filename: loop-payable-invoices-api-openapi.yml
  format: yaml
  label: Loop Payable Invoices API
  slug: loop-payable-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loop/openapi/loop-payable-invoices-api-openapi.yml
- filename: loop-payments-api-openapi.yml
  format: yaml
  label: Loop Payments API
  slug: loop-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loop/openapi/loop-payments-api-openapi.yml
- filename: loop-ping-api-openapi.yml
  format: yaml
  label: Loop Ping API
  slug: loop-ping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loop/openapi/loop-ping-api-openapi.yml
- filename: loop-receivable-invoices-api-openapi.yml
  format: yaml
  label: Loop Receivable Invoices API
  slug: loop-receivable-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loop/openapi/loop-receivable-invoices-api-openapi.yml
- filename: loop-shipment-jobs-api-openapi.yml
  format: yaml
  label: Loop Shipment Jobs API
  slug: loop-shipment-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loop/openapi/loop-shipment-jobs-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Transactions involving any organization, country, or jurisdiction that is blocked or sanctioned by the United States are prohibited.
  entity_types:
  - text: Customer is a legal entity in good standing in the state of Customer’s formation and all jurisdictions in which it conducts business
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned or prohibited activity
    text: 'Customer may not use Customer’s Loop Account or the Services for: (i) any purpose that is illegal, unlawful or prohibited by these Terms, the Agreement'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Loop may limit Customer’s use of certain Services or require that Customer provide additional information to open or maintain Customer’s Loop Account if Loop suspects Customer is or may be engaged in any prohibited activities.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Loop
provenance_date: '2026-11-09'
provider_name: Loop
provider_slug: loop
slug: loop-eligibility
source_date: '2026-11-09'
source_filename: loop-eligibility.yml
source_heading: Eligibility
source_page: https://www.loop.com/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Loop\naid: loop\nurl: https://www.loop.com/legal/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Transactions involving any organization, country, or jurisdiction that is blocked or sanctioned by the United\n    States are prohibited.\nentity_types:\n- type: business\n  text: Customer is a legal entity in good standing in the state of Customer’s formation and all jurisdictions in\n    which it conducts business\nrestricted_uses:\n- summary: Sanctioned or prohibited activity\n  text: 'Customer may not use Customer’s Loop Account or the Services\
  \ for: (i) any purpose that is illegal, unlawful\n    or prohibited by these Terms, the Agreement'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Loop may limit Customer’s use of certain Services or require that Customer provide additional information\n    to open or maintain Customer’s Loop Account if Loop suspects Customer is or may be engaged in any prohibited\n    activities.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/loop/eligibility/loop-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Loop's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Logistics
- Supply Chain
- Freight
- Freight Audit
- Payments
- Transportation
- Artificial Intelligence
- Data Platform
---
