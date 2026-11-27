---
api_specs:
- filename: niural-authentication-api-openapi.yml
  format: yaml
  label: Niural Authentication API
  slug: niural-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/niural/openapi/niural-authentication-api-openapi.yml
- filename: niural-contracts-api-openapi.yml
  format: yaml
  label: Niural Contracts API
  slug: niural-contracts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/niural/openapi/niural-contracts-api-openapi.yml
- filename: niural-invoices-api-openapi.yml
  format: yaml
  label: Niural Invoices API
  slug: niural-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/niural/openapi/niural-invoices-api-openapi.yml
- filename: niural-transactions-api-openapi.yml
  format: yaml
  label: Niural Transactions API
  slug: niural-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/niural/openapi/niural-transactions-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Niural Services are only available for persons in those jurisdictions in which they may legally be sold.
  entity_types:
  - text: If you are registering for a Niural account or using the Niural Services on behalf of an entity or other organization, references to
    type: business
  minimum_age:
    text: at least thirteen (13) years of age in the United States and territories not subject to the GDPR and FADP (each as defined in the DPA); and (y) sixteen (16) years of age in territories subject to the GDPR and FADP
    value: 13 (US); 16 (GDPR/FADP territories)
  restricted_uses:
  - summary: Illegal, harassing or disruptive use
    text: Use the Services for illegal, harassing, unethical, or disruptive purposes
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
name: Niural
provenance_date: '2026-11-10'
provider_name: Niural
provider_slug: niural
slug: niural-eligibility
source_date: '2026-11-10'
source_filename: niural-eligibility.yml
source_heading: Eligibility
source_page: https://www.niural.com/legal/customer-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Niural\naid: niural\nurl: https://www.niural.com/legal/customer-terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Niural Services are only available for persons in those jurisdictions in which they may legally be sold.\nentity_types:\n- type: business\n  text: If you are registering for a Niural account or using the Niural Services on behalf of an entity or other\n    organization, references to\nrestricted_uses:\n- summary: Illegal, harassing or disruptive use\n  text: Use the Services for illegal, harassing, unethical, or disruptive purposes\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: 13 (US); 16 (GDPR/FADP territories)\n  text: at least thirteen (13) years of age in the United States and territories not subject to the GDPR and FADP\n    (each as defined in the DPA); and (y) sixteen (16) years of age in territories subject to the GDPR and FADP\n"
source_yaml_url: https://artifacts.apis.io/niural/eligibility/niural-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Niural's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payroll
- Human Resources
- Employer of Record
- Contractor Management
- Global Payments
- Invoicing
- Compliance
- Fintech
---
