---
api_specs:
- filename: wingspan-1099-operations-api-openapi.yml
  format: yaml
  label: Wingspan 1099 Operations API
  slug: wingspan-1099-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wingspan/openapi/wingspan-1099-operations-api-openapi.yml
- filename: wingspan-banking-management-api-openapi.yml
  format: yaml
  label: Wingspan Banking Management API
  slug: wingspan-banking-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wingspan/openapi/wingspan-banking-management-api-openapi.yml
- filename: wingspan-bulk-operations-api-openapi.yml
  format: yaml
  label: Wingspan Bulk Operations API
  slug: wingspan-bulk-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wingspan/openapi/wingspan-bulk-operations-api-openapi.yml
- filename: wingspan-client-management-api-openapi.yml
  format: yaml
  label: Wingspan Client Management API
  slug: wingspan-client-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wingspan/openapi/wingspan-client-management-api-openapi.yml
- filename: wingspan-collaborator-management-api-openapi.yml
  format: yaml
  label: Wingspan Collaborator Management API
  slug: wingspan-collaborator-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wingspan/openapi/wingspan-collaborator-management-api-openapi.yml
- filename: wingspan-custom-field-management-api-openapi.yml
  format: yaml
  label: Wingspan Custom Field Management API
  slug: wingspan-custom-field-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wingspan/openapi/wingspan-custom-field-management-api-openapi.yml
- filename: wingspan-deprecated-api-openapi.yml
  format: yaml
  label: Wingspan Deprecated API
  slug: wingspan-deprecated-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wingspan/openapi/wingspan-deprecated-api-openapi.yml
- filename: wingspan-document-signing-and-eligibility-api-openapi.yml
  format: yaml
  label: Wingspan Document Signing and Eligibility API
  slug: wingspan-document-signing-and-eligibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wingspan/openapi/wingspan-document-signing-and-eligibility-api-openapi.yml
- filename: wingspan-invoice-management-api-openapi.yml
  format: yaml
  label: Wingspan Invoice Management API
  slug: wingspan-invoice-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wingspan/openapi/wingspan-invoice-management-api-openapi.yml
- filename: wingspan-merchant-category-codes-api-openapi.yml
  format: yaml
  label: Wingspan Merchant Category Codes API
  slug: wingspan-merchant-category-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wingspan/openapi/wingspan-merchant-category-codes-api-openapi.yml
- filename: wingspan-payables-management-api-openapi.yml
  format: yaml
  label: Wingspan Payables Management API
  slug: wingspan-payables-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wingspan/openapi/wingspan-payables-management-api-openapi.yml
- filename: wingspan-payroll-settings-api-openapi.yml
  format: yaml
  label: Wingspan Payroll Settings API
  slug: wingspan-payroll-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wingspan/openapi/wingspan-payroll-settings-api-openapi.yml
- filename: wingspan-reporting-and-analytics-api-openapi.yml
  format: yaml
  label: Wingspan Reporting and Analytics API
  slug: wingspan-reporting-and-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wingspan/openapi/wingspan-reporting-and-analytics-api-openapi.yml
- filename: wingspan-service-settings-api-openapi.yml
  format: yaml
  label: Wingspan Service Settings API
  slug: wingspan-service-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wingspan/openapi/wingspan-service-settings-api-openapi.yml
- filename: wingspan-wingspan-wallet-api-openapi.yml
  format: yaml
  label: Wingspan Wallet API
  slug: wingspan-wingspan-wallet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wingspan/openapi/wingspan-wingspan-wallet-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Wingspan controls and operates this Site from its offices within the United States. If you choose to access this Site ... from another location, you do so on your own initiative and are responsible for compliance with applicable local laws.
  entity_types:
  - text: Confirm that you meet the age of majority and legal competence requirements to enter into a contract
    type: individual
  minimum_age:
    text: You are at least 18 years old and are legally able to enter into a contract
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: By using our Services, you agree to provide accurate information for identity verification purposes and consent to our verification procedures. We may suspend or terminate Services if we cannot verify your identity
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Wingspan
provenance_date: '2026-11-10'
provider_name: Wingspan
provider_slug: wingspan
slug: wingspan-eligibility
source_date: '2026-11-10'
source_filename: wingspan-eligibility.yml
source_heading: Eligibility
source_page: https://www.wingspan.app/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wingspan\naid: wingspan\nurl: https://www.wingspan.app/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Wingspan controls and operates this Site from its offices within the United States. If you choose to access\n    this Site ... from another location, you do so on your own initiative and are responsible for compliance with\n    applicable local laws.\nentity_types:\n- type: individual\n  text: Confirm that you meet the age of majority and legal competence requirements to enter into a contract\nrestricted_uses: []\nverification:\n  kyc: true\n\
  \  kyb: null\n  approval_required: null\n  text: By using our Services, you agree to provide accurate information for identity verification purposes and\n    consent to our verification procedures. We may suspend or terminate Services if we cannot verify your identity\nminimum_age:\n  value: '18'\n  text: You are at least 18 years old and are legally able to enter into a contract\n"
source_yaml_url: https://artifacts.apis.io/wingspan/eligibility/wingspan-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Wingspan's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Payroll
- Contractors
- Invoicing
- Tax
- Fintech
- Freelance Economy
---
