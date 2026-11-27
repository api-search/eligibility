---
api_specs:
- filename: propertyme-connection-api-openapi.yml
  format: yaml
  label: PropertyMe Connection API
  slug: propertyme-connection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propertyme/openapi/propertyme-connection-api-openapi.yml
- filename: propertyme-scope-activities-api-openapi.yml
  format: yaml
  label: 'PropertyMe Scope: Activities API'
  slug: propertyme-scope-activities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propertyme/openapi/propertyme-scope-activities-api-openapi.yml
- filename: propertyme-scope-bills-api-openapi.yml
  format: yaml
  label: 'PropertyMe Scope: Bills API'
  slug: propertyme-scope-bills-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propertyme/openapi/propertyme-scope-bills-api-openapi.yml
- filename: propertyme-scope-contacts-api-openapi.yml
  format: yaml
  label: 'PropertyMe Scope: Contacts API'
  slug: propertyme-scope-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propertyme/openapi/propertyme-scope-contacts-api-openapi.yml
- filename: propertyme-scope-messages-api-openapi.yml
  format: yaml
  label: 'PropertyMe Scope: Messages API'
  slug: propertyme-scope-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propertyme/openapi/propertyme-scope-messages-api-openapi.yml
- filename: propertyme-scope-properties-api-openapi.yml
  format: yaml
  label: 'PropertyMe Scope: Properties API'
  slug: propertyme-scope-properties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propertyme/openapi/propertyme-scope-properties-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    - NZ
    text: The Website is intended for users within Australia and New Zealand only.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful purposes only
    text: You must only use the Services for lawful purposes
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
name: PropertyMe
provenance_date: '2026-11-10'
provider_name: PropertyMe
provider_slug: propertyme
slug: propertyme-eligibility
source_date: '2026-11-10'
source_filename: propertyme-eligibility.yml
source_heading: Eligibility
source_page: https://www.propertyme.com.au/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PropertyMe\naid: propertyme\nurl: https://www.propertyme.com.au/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  - NZ\n  excluded: []\n  text: The Website is intended for users within Australia and New Zealand only.\nentity_types: []\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You must only use the Services for lawful purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/propertyme/eligibility/propertyme-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from PropertyMe's own page on 2026-11-10.
synthetic: false
tags:
- Real Estate
- Australia
- Property Management
- Rentals
- PropTech
- Tenancy
- Trust Accounting
- Inspection
- Maintenance
- Documents
- Payments
- New Zealand
---
