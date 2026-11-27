---
api_specs:
- filename: appzen-chart-of-accounts-api-openapi.yml
  format: yaml
  label: AppZen Chart of Accounts API
  slug: appzen-chart-of-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appzen/openapi/appzen-chart-of-accounts-api-openapi.yml
- filename: appzen-custom-data-sets-api-openapi.yml
  format: yaml
  label: AppZen Custom Data Sets API
  slug: appzen-custom-data-sets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appzen/openapi/appzen-custom-data-sets-api-openapi.yml
- filename: appzen-documents-api-openapi.yml
  format: yaml
  label: AppZen Documents API
  slug: appzen-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appzen/openapi/appzen-documents-api-openapi.yml
- filename: appzen-entities-api-openapi.yml
  format: yaml
  label: AppZen Entities API
  slug: appzen-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appzen/openapi/appzen-entities-api-openapi.yml
- filename: appzen-externally-processed-invoices-api-openapi.yml
  format: yaml
  label: AppZen Externally Processed Invoices API
  slug: appzen-externally-processed-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appzen/openapi/appzen-externally-processed-invoices-api-openapi.yml
- filename: appzen-goods-receipt-api-openapi.yml
  format: yaml
  label: AppZen Goods Receipt API
  slug: appzen-goods-receipt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appzen/openapi/appzen-goods-receipt-api-openapi.yml
- filename: appzen-invoice-audit-results-api-openapi.yml
  format: yaml
  label: AppZen Invoice Audit Results API
  slug: appzen-invoice-audit-results-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appzen/openapi/appzen-invoice-audit-results-api-openapi.yml
- filename: appzen-invoice-status-sync-api-openapi.yml
  format: yaml
  label: AppZen Invoice Status Sync API
  slug: appzen-invoice-status-sync-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appzen/openapi/appzen-invoice-status-sync-api-openapi.yml
- filename: appzen-invoices-api-openapi.yml
  format: yaml
  label: AppZen Invoices API
  slug: appzen-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appzen/openapi/appzen-invoices-api-openapi.yml
- filename: appzen-lookup-item-api-openapi.yml
  format: yaml
  label: AppZen Lookup Item API
  slug: appzen-lookup-item-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appzen/openapi/appzen-lookup-item-api-openapi.yml
- filename: appzen-lookup-table-api-openapi.yml
  format: yaml
  label: AppZen Lookup Table API
  slug: appzen-lookup-table-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appzen/openapi/appzen-lookup-table-api-openapi.yml
- filename: appzen-payment-terms-api-openapi.yml
  format: yaml
  label: AppZen Payment Terms API
  slug: appzen-payment-terms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appzen/openapi/appzen-payment-terms-api-openapi.yml
- filename: appzen-processed-invoices-api-openapi.yml
  format: yaml
  label: AppZen Processed Invoices API
  slug: appzen-processed-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appzen/openapi/appzen-processed-invoices-api-openapi.yml
- filename: appzen-purchase-orders-api-openapi.yml
  format: yaml
  label: AppZen Purchase Orders API
  slug: appzen-purchase-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appzen/openapi/appzen-purchase-orders-api-openapi.yml
- filename: appzen-suppliers-api-openapi.yml
  format: yaml
  label: AppZen Suppliers API
  slug: appzen-suppliers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appzen/openapi/appzen-suppliers-api-openapi.yml
- filename: appzen-tax-master-api-openapi.yml
  format: yaml
  label: AppZen Tax Master API
  slug: appzen-tax-master-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appzen/openapi/appzen-tax-master-api-openapi.yml
- filename: appzen-unit-of-measures-api-openapi.yml
  format: yaml
  label: AppZen Unit of Measures API
  slug: appzen-unit-of-measures-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appzen/openapi/appzen-unit-of-measures-api-openapi.yml
- filename: appzen-user-groups-api-openapi.yml
  format: yaml
  label: AppZen User Groups API
  slug: appzen-user-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appzen/openapi/appzen-user-groups-api-openapi.yml
- filename: appzen-vat-api-openapi.yml
  format: yaml
  label: AppZen Vat API
  slug: appzen-vat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appzen/openapi/appzen-vat-api-openapi.yml
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
  - summary: Not for time-critical or mission-critical functions
    text: The Customer agrees that the Subscription Service will not be used, and is not licensed for use, in connection with any of the Customer’s time-critical or mission-critical functions.
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
name: AppZen
provenance_date: '2026-11-09'
provider_name: AppZen
provider_slug: appzen
slug: appzen-eligibility
source_date: '2026-11-09'
source_filename: appzen-eligibility.yml
source_heading: Eligibility
source_page: https://www.appzen.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AppZen\naid: appzen\nurl: https://www.appzen.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Not for time-critical or mission-critical functions\n  text: The Customer agrees that the Subscription Service will not be used, and is not licensed for use, in connection\n    with any of the Customer’s time-critical or mission-critical functions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/appzen/eligibility/appzen-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from AppZen's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Accounts Payable
- Expense Management
- Invoice Processing
- Spend Audit
- Artificial Intelligence
- ERP Integration
---
