---
api_specs:
- filename: innago-expenses-api-openapi.yml
  format: yaml
  label: Innago Expenses API
  slug: innago-expenses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/innago/openapi/innago-expenses-api-openapi.yml
- filename: innago-external-references-api-openapi.yml
  format: yaml
  label: Innago External References API
  slug: innago-external-references-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/innago/openapi/innago-external-references-api-openapi.yml
- filename: innago-health-api-openapi.yml
  format: yaml
  label: Innago Health API
  slug: innago-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/innago/openapi/innago-health-api-openapi.yml
- filename: innago-invoices-api-openapi.yml
  format: yaml
  label: Innago Invoices API
  slug: innago-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/innago/openapi/innago-invoices-api-openapi.yml
- filename: innago-leases-api-openapi.yml
  format: yaml
  label: Innago Leases API
  slug: innago-leases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/innago/openapi/innago-leases-api-openapi.yml
- filename: innago-maintenance-api-openapi.yml
  format: yaml
  label: Innago Maintenance API
  slug: innago-maintenance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/innago/openapi/innago-maintenance-api-openapi.yml
- filename: innago-payments-api-openapi.yml
  format: yaml
  label: Innago Payments API
  slug: innago-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/innago/openapi/innago-payments-api-openapi.yml
- filename: innago-properties-api-openapi.yml
  format: yaml
  label: Innago Properties API
  slug: innago-properties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/innago/openapi/innago-properties-api-openapi.yml
- filename: innago-tenants-api-openapi.yml
  format: yaml
  label: Innago Tenants API
  slug: innago-tenants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/innago/openapi/innago-tenants-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: In accessing the Site, you represent and warrant that you are not located in a country subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a “terrorist supporting” country
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or fair-housing-violating use
    text: You agree not to use the Service for any illegal purpose or in any manner inconsistent with these Terms.
  - summary: Discriminatory refusal to lease
    text: Landlord agrees that it shall not refuse to display, lease or sublease property posted on the Service to any person due to such person’s race, color, religion, national origin, sex, familial status, physical disability or any other legally protected class of individuals
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
name: Innago
provenance_date: '2026-11-09'
provider_name: Innago
provider_slug: innago
slug: innago-eligibility
source_date: '2026-11-09'
source_filename: innago-eligibility.yml
source_heading: Eligibility
source_page: https://auth.innago.com/termsandcondition
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Innago\naid: innago\nurl: https://auth.innago.com/termsandcondition\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: In accessing the Site, you represent and warrant that you are not located in a country subject to a U.S.\n    Government embargo, or that has been designated by the U.S. Government as a “terrorist supporting” country\nentity_types: []\nrestricted_uses:\n- summary: Illegal or fair-housing-violating use\n  text: You agree not to use the Service for any illegal purpose or in any manner inconsistent with these Terms.\n- summary: Discriminatory refusal\
  \ to lease\n  text: Landlord agrees that it shall not refuse to display, lease or sublease property posted on the Service to\n    any person due to such person’s race, color, religion, national origin, sex, familial status, physical disability\n    or any other legally protected class of individuals\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/innago/eligibility/innago-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from Innago's own page on 2026-11-09.
synthetic: false
tags:
- Property Management
- Real Estate
- Leases
- Rent Collection
- Maintenance
- Tenants
- Invoicing
- Payments
---
