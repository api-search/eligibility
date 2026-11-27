---
api_specs:
- filename: autofi-authorization-api-openapi.yml
  format: yaml
  label: AutoFi Authorization API
  slug: autofi-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autofi/openapi/autofi-authorization-api-openapi.yml
- filename: autofi-calculate-payment-api-openapi.yml
  format: yaml
  label: AutoFi Calculate Payment API
  slug: autofi-calculate-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autofi/openapi/autofi-calculate-payment-api-openapi.yml
- filename: autofi-dealers-api-openapi.yml
  format: yaml
  label: AutoFi Dealers API
  slug: autofi-dealers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autofi/openapi/autofi-dealers-api-openapi.yml
- filename: autofi-dealmaker-api-openapi.yml
  format: yaml
  label: AutoFi Dealmaker API
  slug: autofi-dealmaker-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autofi/openapi/autofi-dealmaker-api-openapi.yml
- filename: autofi-loan-applications-api-openapi.yml
  format: yaml
  label: AutoFi Loan Applications API
  slug: autofi-loan-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autofi/openapi/autofi-loan-applications-api-openapi.yml
- filename: autofi-prequalification-api-openapi.yml
  format: yaml
  label: AutoFi Prequalification API
  slug: autofi-prequalification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autofi/openapi/autofi-prequalification-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services may not be available in all geographic areas and eligibility for any particular Service shall be subject to AutoFi’s discretion.
  entity_types:
  - text: Licensee is a corporation, limited liability company, or limited partnership, duly organized, validly existing, qualified and authorized to transact business
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use on devices not owned or controlled
    text: The rights and licenses granted under this Agreement do not allow Licensee or its Affiliates to use the Services on any device that Licensee or its Affiliates do not own or control
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
name: AutoFi
provenance_date: '2026-11-09'
provider_name: AutoFi
provider_slug: autofi
slug: autofi-eligibility
source_date: '2026-11-09'
source_filename: autofi-eligibility.yml
source_heading: Eligibility
source_page: https://www.autofi.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AutoFi\naid: autofi\nurl: https://www.autofi.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Services may not be available in all geographic areas and eligibility for any particular Service shall\n    be subject to AutoFi’s discretion.\nentity_types:\n- type: business\n  text: Licensee is a corporation, limited liability company, or limited partnership, duly organized, validly existing,\n    qualified and authorized to transact business\nrestricted_uses:\n- summary: Use on devices not owned or controlled\n  text: The rights and licenses\
  \ granted under this Agreement do not allow Licensee or its Affiliates to use the\n    Services on any device that Licensee or its Affiliates do not own or control\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/autofi/eligibility/autofi-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from AutoFi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Automotive
- Fintech
- Digital Retail
- Auto Finance
- Dealership
- Sales Enablement
- Software-as-a-Service
- Lending
- Loan Origination
- Credit Decisioning
- Payment Calculation
- Prequalification
---
