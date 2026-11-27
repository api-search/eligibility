---
api_specs:
- filename: flowaccount-billingnote-api-openapi.yml
  format: yaml
  label: FlowAccount BillingNote API
  slug: flowaccount-billingnote-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flowaccount/openapi/flowaccount-billingnote-api-openapi.yml
- filename: flowaccount-cashinvoice-api-openapi.yml
  format: yaml
  label: FlowAccount CashInvoice API
  slug: flowaccount-cashinvoice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flowaccount/openapi/flowaccount-cashinvoice-api-openapi.yml
- filename: flowaccount-companycurrency-api-openapi.yml
  format: yaml
  label: FlowAccount CompanyCurrency API
  slug: flowaccount-companycurrency-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flowaccount/openapi/flowaccount-companycurrency-api-openapi.yml
- filename: flowaccount-contact-api-openapi.yml
  format: yaml
  label: FlowAccount Contact API
  slug: flowaccount-contact-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flowaccount/openapi/flowaccount-contact-api-openapi.yml
- filename: flowaccount-debitnote-api-openapi.yml
  format: yaml
  label: FlowAccount DebitNote API
  slug: flowaccount-debitnote-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flowaccount/openapi/flowaccount-debitnote-api-openapi.yml
- filename: flowaccount-employee-api-openapi.yml
  format: yaml
  label: FlowAccount Employee API
  slug: flowaccount-employee-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flowaccount/openapi/flowaccount-employee-api-openapi.yml
- filename: flowaccount-expense-api-openapi.yml
  format: yaml
  label: FlowAccount Expense API
  slug: flowaccount-expense-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flowaccount/openapi/flowaccount-expense-api-openapi.yml
- filename: flowaccount-products-api-openapi.yml
  format: yaml
  label: FlowAccount Products API
  slug: flowaccount-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flowaccount/openapi/flowaccount-products-api-openapi.yml
- filename: flowaccount-productunit-api-openapi.yml
  format: yaml
  label: FlowAccount ProductUnit API
  slug: flowaccount-productunit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flowaccount/openapi/flowaccount-productunit-api-openapi.yml
- filename: flowaccount-purchase-api-openapi.yml
  format: yaml
  label: FlowAccount Purchase API
  slug: flowaccount-purchase-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flowaccount/openapi/flowaccount-purchase-api-openapi.yml
- filename: flowaccount-quotation-api-openapi.yml
  format: yaml
  label: FlowAccount Quotation API
  slug: flowaccount-quotation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flowaccount/openapi/flowaccount-quotation-api-openapi.yml
- filename: flowaccount-receipt-api-openapi.yml
  format: yaml
  label: FlowAccount Receipt API
  slug: flowaccount-receipt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flowaccount/openapi/flowaccount-receipt-api-openapi.yml
- filename: flowaccount-receivableinvoice-api-openapi.yml
  format: yaml
  label: FlowAccount ReceivableInvoice API
  slug: flowaccount-receivableinvoice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flowaccount/openapi/flowaccount-receivableinvoice-api-openapi.yml
- filename: flowaccount-taxinvoice-api-openapi.yml
  format: yaml
  label: FlowAccount TaxInvoice API
  slug: flowaccount-taxinvoice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flowaccount/openapi/flowaccount-taxinvoice-api-openapi.yml
- filename: flowaccount-batch-import-api-openapi.yml
  format: yaml
  label: FlowAccount Batch Import API
  slug: flowaccount-batch-import-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flowaccount/openapi/flowaccount-batch-import-api-openapi.yml
- filename: flowaccount-credit-note-api-openapi.yml
  format: yaml
  label: FlowAccount Credit Note API
  slug: flowaccount-credit-note-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flowaccount/openapi/flowaccount-credit-note-api-openapi.yml
- filename: flowaccount-product-category-api-openapi.yml
  format: yaml
  label: FlowAccount Product Category API
  slug: flowaccount-product-category-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flowaccount/openapi/flowaccount-product-category-api-openapi.yml
- filename: flowaccount-product-inventory-api-openapi.yml
  format: yaml
  label: FlowAccount Product Inventory API
  slug: flowaccount-product-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flowaccount/openapi/flowaccount-product-inventory-api-openapi.yml
- filename: flowaccount-purchase-order-api-openapi.yml
  format: yaml
  label: FlowAccount Purchase Order API
  slug: flowaccount-purchase-order-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flowaccount/openapi/flowaccount-purchase-order-api-openapi.yml
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
  - summary: Lawful use only
    text: ผู้ใช้บริการต้องใช้บริการของผู้ให้บริการโดยสุจริต และชอบด้วยกฎหมายเท่านั้น
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
name: FlowAccount
provenance_date: '2026-11-09'
provider_name: FlowAccount
provider_slug: flowaccount
slug: flowaccount-eligibility
source_date: '2026-11-09'
source_filename: flowaccount-eligibility.yml
source_heading: Eligibility
source_page: https://flowaccount.com/term-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FlowAccount\naid: flowaccount\nurl: https://flowaccount.com/term-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Lawful use only\n  text: ผู้ใช้บริการต้องใช้บริการของผู้ให้บริการโดยสุจริต และชอบด้วยกฎหมายเท่านั้น\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/flowaccount/eligibility/flowaccount-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from FlowAccount's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Accounting
- Invoicing
- Payroll
- Point-of-Sale
- Small Business
- Finance
- Tax
- Thailand
- Bookkeeping
---
