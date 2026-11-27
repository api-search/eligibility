---
api_specs:
- filename: pge-applicationinformation-api-openapi.yml
  format: yaml
  label: Pacific Gas and Electric Application Information API
  slug: pge-applicationinformation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pge/openapi/pge-applicationinformation-api-openapi.yml
- filename: pge-authorization-api-openapi.yml
  format: yaml
  label: Pacific Gas and Electric Authorization API
  slug: pge-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pge/openapi/pge-authorization-api-openapi.yml
- filename: pge-batch-api-openapi.yml
  format: yaml
  label: Pacific Gas and Electric Batch API
  slug: pge-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pge/openapi/pge-batch-api-openapi.yml
- filename: pge-usagepoint-api-openapi.yml
  format: yaml
  label: Pacific Gas and Electric Usage Point API
  slug: pge-usagepoint-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pge/openapi/pge-usagepoint-api-openapi.yml
- filename: pge-subscriptions-api-openapi.yml
  format: yaml
  label: Pacific Gas and Electric Subscriptions API
  slug: pge-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pge/openapi/pge-subscriptions-api-openapi.yml
- filename: pge-usage-api-openapi.yml
  format: yaml
  label: Pacific Gas and Electric Usage API
  slug: pge-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pge/openapi/pge-usage-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “Applicant” means the entity registering to use the Share My Data Platform.
    type: other
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: PG&E reserves the right to reject any Registration application that does not complete connectivity testing within the allotted timeframe of 90 days.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Pacific Gas and Electric
provenance_date: '2026-11-10'
provider_name: Pacific Gas and Electric
provider_slug: pge
slug: pge-eligibility
source_date: '2026-11-10'
source_filename: pge-eligibility.yml
source_heading: Eligibility
source_page: https://www.pge.com/assets/pge/docs/save-energy-and-money/energy-savings-programs/ShareMyData_Platform_TermsofUse.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pacific Gas and Electric\naid: pge\nurl: https://www.pge.com/assets/pge/docs/save-energy-and-money/energy-savings-programs/ShareMyData_Platform_TermsofUse.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: “Applicant” means the entity registering to use the Share My Data Platform.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: PG&E reserves the right to reject any Registration application that does not complete connectivity testing\n    within the allotted timeframe of 90 days.\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pge/eligibility/pge-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from Pacific Gas and Electric's own page on 2026-11-10.
synthetic: false
tags:
- Energy
- United States
- Utilities
- Electricity
- Gas
- California
- Smart Metering
- Green Button
- ESPI
- Energy Data
- Grid
- Demand Response
- Investor-Owned Utility
---
