---
api_specs:
- filename: cariqa-billing-details-api-openapi.yml
  format: yaml
  label: Cariqa Billing Details API
  slug: cariqa-billing-details-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cariqa/openapi/cariqa-billing-details-api-openapi.yml
- filename: cariqa-charging-sessions-api-openapi.yml
  format: yaml
  label: Cariqa Charging Sessions API
  slug: cariqa-charging-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cariqa/openapi/cariqa-charging-sessions-api-openapi.yml
- filename: cariqa-debts-api-openapi.yml
  format: yaml
  label: Cariqa Debts API
  slug: cariqa-debts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cariqa/openapi/cariqa-debts-api-openapi.yml
- filename: cariqa-invoices-api-openapi.yml
  format: yaml
  label: Cariqa Invoices API
  slug: cariqa-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cariqa/openapi/cariqa-invoices-api-openapi.yml
- filename: cariqa-payments-api-openapi.yml
  format: yaml
  label: Cariqa Payments API
  slug: cariqa-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cariqa/openapi/cariqa-payments-api-openapi.yml
- filename: cariqa-stations-api-openapi.yml
  format: yaml
  label: Cariqa Stations API
  slug: cariqa-stations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cariqa/openapi/cariqa-stations-api-openapi.yml
- filename: cariqa-users-api-openapi.yml
  format: yaml
  label: Cariqa Users API
  slug: cariqa-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cariqa/openapi/cariqa-users-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - DE
    text: Cariqa delivers only to customers who have their habitual residence (billing address) in Germany and can provide a delivery address within Germany.
  entity_types:
  - text: The Services may only be used by individuals who are at least 18 years of age.
    type: individual
  - text: The Terms of Use apply regardless of whether you are a consumer, entrepreneur or merchant.
    type: business
  minimum_age:
    text: The Services may only be used by individuals who are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Commercial, business or professional use prohibited
    text: use the Service for private purposes only and not for commercial, business or professional purposes
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
name: Cariqa
provenance_date: '2026-11-09'
provider_name: Cariqa
provider_slug: cariqa
slug: cariqa-eligibility
source_date: '2026-11-09'
source_filename: cariqa-eligibility.yml
source_heading: Eligibility
source_page: https://www.cariqa.com/en/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cariqa\naid: cariqa\nurl: https://www.cariqa.com/en/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - DE\n  excluded: []\n  text: Cariqa delivers only to customers who have their habitual residence (billing address) in Germany and can\n    provide a delivery address within Germany.\nentity_types:\n- type: individual\n  text: The Services may only be used by individuals who are at least 18 years of age.\n- type: business\n  text: The Terms of Use apply regardless of whether you are a consumer, entrepreneur or merchant.\nrestricted_uses:\n- summary: Commercial, business or professional use\
  \ prohibited\n  text: use the Service for private purposes only and not for commercial, business or professional purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services may only be used by individuals who are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/cariqa/eligibility/cariqa-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Cariqa's own page on 2026-11-09.
synthetic: false
tags:
- Company
- EV Charging
- Electric Vehicles
- Payments
- Mobility
- E-Mobility
- Charge Point Operator
- Energy
---
