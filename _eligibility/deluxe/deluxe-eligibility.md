---
api_specs:
- filename: deluxe-american-api-openapi.yml
  format: yaml
  label: Deluxe Corporation American API
  slug: deluxe-american-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deluxe/openapi/deluxe-american-api-openapi.yml
- filename: deluxe-batches-api-openapi.yml
  format: yaml
  label: Deluxe Corporation Batches API
  slug: deluxe-batches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deluxe/openapi/deluxe-batches-api-openapi.yml
- filename: deluxe-customers-api-openapi.yml
  format: yaml
  label: Deluxe Corporation Customers API
  slug: deluxe-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deluxe/openapi/deluxe-customers-api-openapi.yml
- filename: deluxe-emv-api-openapi.yml
  format: yaml
  label: Deluxe Corporation Emv API
  slug: deluxe-emv-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deluxe/openapi/deluxe-emv-api-openapi.yml
- filename: deluxe-events-api-openapi.yml
  format: yaml
  label: Deluxe Corporation Events API
  slug: deluxe-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deluxe/openapi/deluxe-events-api-openapi.yml
- filename: deluxe-invoices-api-openapi.yml
  format: yaml
  label: Deluxe Corporation Invoices API
  slug: deluxe-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deluxe/openapi/deluxe-invoices-api-openapi.yml
- filename: deluxe-payments-api-openapi.yml
  format: yaml
  label: Deluxe Corporation Payments API
  slug: deluxe-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deluxe/openapi/deluxe-payments-api-openapi.yml
- filename: deluxe-refunds-api-openapi.yml
  format: yaml
  label: Deluxe Corporation Refunds API
  slug: deluxe-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deluxe/openapi/deluxe-refunds-api-openapi.yml
- filename: deluxe-reports-api-openapi.yml
  format: yaml
  label: Deluxe Corporation Reports API
  slug: deluxe-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deluxe/openapi/deluxe-reports-api-openapi.yml
- filename: deluxe-secservices-api-openapi.yml
  format: yaml
  label: Deluxe Corporation Secservices API
  slug: deluxe-secservices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deluxe/openapi/deluxe-secservices-api-openapi.yml
- filename: deluxe-subscriptions-api-openapi.yml
  format: yaml
  label: Deluxe Corporation Subscriptions API
  slug: deluxe-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deluxe/openapi/deluxe-subscriptions-api-openapi.yml
- filename: deluxe-payment-links-api-openapi.yml
  format: yaml
  label: Deluxe Payment Links API
  slug: deluxe-payment-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deluxe/openapi/deluxe-payment-links-api-openapi.yml
- filename: deluxe-payment-methods-api-openapi.yml
  format: yaml
  label: Deluxe Payment Methods API
  slug: deluxe-payment-methods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deluxe/openapi/deluxe-payment-methods-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: This Site is offered and available to users who are 16 years of age or older and reside in the United States ("US"), Canada, or any of the territories or possessions of the US or Canada.
  entity_types:
  - text: If you are agreeing to these Terms or any other agreement for a particular Deluxe Service on behalf of a corporate entity, you represent and warrant that you have the legal authority to similarly bind such corporate entity
    type: business
  minimum_age:
    text: This Site is offered and available to users who are 16 years of age or older
    value: '16'
  restricted_uses:
  - summary: No unlawful or harmful use
    text: You may only use the Site for lawful purposes and in accordance with these Terms.
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
name: Deluxe
provenance_date: '2026-11-09'
provider_name: Deluxe
provider_slug: deluxe
slug: deluxe-eligibility
source_date: '2026-11-09'
source_filename: deluxe-eligibility.yml
source_heading: Eligibility
source_page: https://www.deluxe.com/policy/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Deluxe\naid: deluxe\nurl: https://www.deluxe.com/policy/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: This Site is offered and available to users who are 16 years of age or older and reside in the United States\n    (\"US\"), Canada, or any of the territories or possessions of the US or Canada.\nentity_types:\n- type: business\n  text: If you are agreeing to these Terms or any other agreement for a particular Deluxe Service on behalf of a\n    corporate entity, you represent and warrant that you have the legal authority to similarly bind such corporate\n\
  \    entity\nrestricted_uses:\n- summary: No unlawful or harmful use\n  text: You may only use the Site for lawful purposes and in accordance with these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: This Site is offered and available to users who are 16 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/deluxe/eligibility/deluxe-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Deluxe's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Merchant Services
- Card Processing
- ACH
- Invoicing
- Subscription
- Tokenization
- Webhook
- Reporting
- Data Analytics
- Marketing
- Small Business
---
