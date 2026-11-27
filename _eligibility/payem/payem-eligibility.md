---
api_specs:
- filename: payem-ai-discovery-api-openapi.yml
  format: yaml
  label: Payem AI Discovery API
  slug: payem-ai-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payem/openapi/payem-ai-discovery-api-openapi.yml
- filename: payem-business-api-openapi.yml
  format: yaml
  label: Payem Business API
  slug: payem-business-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payem/openapi/payem-business-api-openapi.yml
- filename: payem-categories-api-openapi.yml
  format: yaml
  label: Payem Categories API
  slug: payem-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payem/openapi/payem-categories-api-openapi.yml
- filename: payem-faq-api-openapi.yml
  format: yaml
  label: Payem Faq API
  slug: payem-faq-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payem/openapi/payem-faq-api-openapi.yml
- filename: payem-qa-api-openapi.yml
  format: yaml
  label: Payem Qa API
  slug: payem-qa-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payem/openapi/payem-qa-api-openapi.yml
- filename: payem-search-api-openapi.yml
  format: yaml
  label: Payem Search API
  slug: payem-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payem/openapi/payem-search-api-openapi.yml
- filename: payem-testimonials-api-openapi.yml
  format: yaml
  label: Payem Testimonials API
  slug: payem-testimonials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payem/openapi/payem-testimonials-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer will not access or use the Platform or the PayEm Cards if Customer or any Authorized Users are located in any jurisdiction in which the provision of the services, Platform, software, or other components is prohibited under U.S. or Israel or other applicable laws or regulations
  entity_types:
  - text: PayEm Cards may only be used for bona fide business-related Charges and may not be used for personal, family, or household purposes.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Money laundering or terror financing
    text: use the Platform or the PayEm Cards in connection with any money laundering or terror financing
  - summary: Payroll funding
    text: use the Platform to fund or remit payroll or payroll deposits
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: the PayEm Card will be provided subject to Customer successfully completing and meeting PayEm’s KYC and due diligence requirements.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Payem
provenance_date: '2026-11-10'
provider_name: Payem
provider_slug: payem
slug: payem-eligibility
source_date: '2026-11-10'
source_filename: payem-eligibility.yml
source_heading: Eligibility
source_page: https://www.payem.co/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Payem\naid: payem\nurl: https://www.payem.co/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer will not access or use the Platform or the PayEm Cards if Customer or any Authorized Users are\n    located in any jurisdiction in which the provision of the services, Platform, software, or other components\n    is prohibited under U.S. or Israel or other applicable laws or regulations\nentity_types:\n- type: business\n  text: PayEm Cards may only be used for bona fide business-related Charges and may not be used for personal, family,\n    or household purposes.\n\
  restricted_uses:\n- summary: Money laundering or terror financing\n  text: use the Platform or the PayEm Cards in connection with any money laundering or terror financing\n- summary: Payroll funding\n  text: use the Platform to fund or remit payroll or payroll deposits\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: the PayEm Card will be provided subject to Customer successfully completing and meeting PayEm’s KYC and\n    due diligence requirements.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/payem/eligibility/payem-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Payem's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Spend Management
- Procurement
- Accounts Payable
- Corporate Cards
- Expense Management
- Financial Operations
- Invoice Processing
- Fintech
- ERP Integration
---
