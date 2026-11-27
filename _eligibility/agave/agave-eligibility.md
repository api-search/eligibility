---
api_specs:
- filename: agave-budgets-api-openapi.yml
  format: yaml
  label: Agave Budgets API
  slug: agave-budgets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agave/openapi/agave-budgets-api-openapi.yml
- filename: agave-contracts-api-openapi.yml
  format: yaml
  label: Agave Contracts API
  slug: agave-contracts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agave/openapi/agave-contracts-api-openapi.yml
- filename: agave-cost-codes-api-openapi.yml
  format: yaml
  label: Agave Cost Codes API
  slug: agave-cost-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agave/openapi/agave-cost-codes-api-openapi.yml
- filename: agave-employees-api-openapi.yml
  format: yaml
  label: Agave Employees API
  slug: agave-employees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agave/openapi/agave-employees-api-openapi.yml
- filename: agave-invoices-api-openapi.yml
  format: yaml
  label: Agave Invoices API
  slug: agave-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agave/openapi/agave-invoices-api-openapi.yml
- filename: agave-link-sessions-api-openapi.yml
  format: yaml
  label: Agave Link Sessions API
  slug: agave-link-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agave/openapi/agave-link-sessions-api-openapi.yml
- filename: agave-projects-api-openapi.yml
  format: yaml
  label: Agave Projects API
  slug: agave-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agave/openapi/agave-projects-api-openapi.yml
- filename: agave-timesheets-api-openapi.yml
  format: yaml
  label: Agave Timesheets API
  slug: agave-timesheets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agave/openapi/agave-timesheets-api-openapi.yml
- filename: agave-vendors-api-openapi.yml
  format: yaml
  label: Agave Vendors API
  slug: agave-vendors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agave/openapi/agave-vendors-api-openapi.yml
- filename: agave-common-api-openapi.yml
  format: yaml
  label: Agave Common API
  slug: agave-common-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agave/openapi/agave-common-api-openapi.yml
- filename: agave-customer-management-api-openapi.yml
  format: yaml
  label: Agave Customer Management API
  slug: agave-customer-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agave/openapi/agave-customer-management-api-openapi.yml
- filename: agave-file-management-api-openapi.yml
  format: yaml
  label: Agave File Management API
  slug: agave-file-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agave/openapi/agave-file-management-api-openapi.yml
- filename: agave-financials-management-api-openapi.yml
  format: yaml
  label: Agave Financials Management API
  slug: agave-financials-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agave/openapi/agave-financials-management-api-openapi.yml
- filename: agave-project-management-api-openapi.yml
  format: yaml
  label: Agave Project Management API
  slug: agave-project-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agave/openapi/agave-project-management-api-openapi.yml
- filename: agave-service-management-api-openapi.yml
  format: yaml
  label: Agave Service Management API
  slug: agave-service-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agave/openapi/agave-service-management-api-openapi.yml
- filename: agave-webhooks-api-openapi.yml
  format: yaml
  label: Agave Webhooks API
  slug: agave-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agave/openapi/agave-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Site is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  minimum_age:
    text: The Site is intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: HIPAA/FISMA-regulated interactions
    text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use this Site.
  - summary: GLBA-violating use
    text: You may not use the Site in a way that would violate the Gramm-Leach-Bliley Act (GLBA).
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
name: Agave
provenance_date: '2026-11-09'
provider_name: Agave
provider_slug: agave
slug: agave-eligibility
source_date: '2026-11-09'
source_filename: agave-eligibility.yml
source_heading: Eligibility
source_page: https://useagave.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agave\naid: agave\nurl: https://useagave.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Site is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types: []\nrestricted_uses:\n- summary: HIPAA/FISMA-regulated interactions\n  text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability and\n    Accountability Act (HIPAA), Federal Information Security Management Act (FISMA),\
  \ etc.), so if your interactions\n    would be subjected to such laws, you may not use this Site.\n- summary: GLBA-violating use\n  text: You may not use the Site in a way that would violate the Gramm-Leach-Bliley Act (GLBA).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/agave/eligibility/agave-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Agave's own page on 2026-11-09.
synthetic: false
tags:
- Accounting
- Construction
- Integration
- ERP
- Project Management
- Unified API
- iPaaS
- Webhook
- Field Service Management
- Invoicing
---
