---
api_specs:
- filename: edf-energy-account-import-api-openapi.yml
  format: yaml
  label: EDF Energy Account Import API
  slug: edf-energy-account-import-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edf-energy/openapi/edf-energy-account-import-api-openapi.yml
- filename: edf-energy-data-import-api-openapi.yml
  format: yaml
  label: EDF Energy Data Import API
  slug: edf-energy-data-import-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edf-energy/openapi/edf-energy-data-import-api-openapi.yml
- filename: edf-energy-external-client-healthcheck-api-openapi.yml
  format: yaml
  label: EDF Energy External Client Healthcheck API
  slug: edf-energy-external-client-healthcheck-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edf-energy/openapi/edf-energy-external-client-healthcheck-api-openapi.yml
- filename: edf-energy-external-events-api-openapi.yml
  format: yaml
  label: EDF Energy External Events API
  slug: edf-energy-external-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edf-energy/openapi/edf-energy-external-events-api-openapi.yml
- filename: edf-energy-post-account-import-api-openapi.yml
  format: yaml
  label: EDF Energy Post Account Import API
  slug: edf-energy-post-account-import-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edf-energy/openapi/edf-energy-post-account-import-api-openapi.yml
- filename: edf-energy-query-api-openapi.yml
  format: yaml
  label: EDF Energy Query API
  slug: edf-energy-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edf-energy/openapi/edf-energy-query-api-openapi.yml
- filename: edf-energy-accounts-api-openapi.yml
  format: yaml
  label: EDF Energy Accounts API
  slug: edf-energy-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edf-energy/openapi/edf-energy-accounts-api-openapi.yml
- filename: edf-energy-electricity-meter-points-api-openapi.yml
  format: yaml
  label: EDF Energy Electricity Meter Points API
  slug: edf-energy-electricity-meter-points-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edf-energy/openapi/edf-energy-electricity-meter-points-api-openapi.yml
- filename: edf-energy-gas-meter-points-api-openapi.yml
  format: yaml
  label: EDF Energy Gas Meter Points API
  slug: edf-energy-gas-meter-points-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edf-energy/openapi/edf-energy-gas-meter-points-api-openapi.yml
- filename: edf-energy-industry-api-openapi.yml
  format: yaml
  label: EDF Energy Industry API
  slug: edf-energy-industry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edf-energy/openapi/edf-energy-industry-api-openapi.yml
- filename: edf-energy-orders-api-openapi.yml
  format: yaml
  label: EDF Energy Orders API
  slug: edf-energy-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edf-energy/openapi/edf-energy-orders-api-openapi.yml
- filename: edf-energy-payment-intents-api-openapi.yml
  format: yaml
  label: EDF Energy Payment Intents API
  slug: edf-energy-payment-intents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edf-energy/openapi/edf-energy-payment-intents-api-openapi.yml
- filename: edf-energy-products-api-openapi.yml
  format: yaml
  label: EDF Energy Products API
  slug: edf-energy-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edf-energy/openapi/edf-energy-products-api-openapi.yml
- filename: edf-energy-quotes-api-openapi.yml
  format: yaml
  label: EDF Energy Quotes API
  slug: edf-energy-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edf-energy/openapi/edf-energy-quotes-api-openapi.yml
- filename: edf-energy-voice-api-openapi.yml
  format: yaml
  label: EDF Energy Voice API
  slug: edf-energy-voice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edf-energy/openapi/edf-energy-voice-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or reputation-damaging use
    text: You must not use the Website for any illegal purpose or for any purpose that in our reasonable opinion damages our reputation or the reputation of any of our Group Companies, customers, suppliers or other users.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Before you can access MyAccount or MyLearningHub you may be required to complete a registration process by providing the information requested by us.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: EDF Energy
provenance_date: '2026-11-09'
provider_name: EDF Energy
provider_slug: edf-energy
slug: edf-energy-eligibility
source_date: '2026-11-09'
source_filename: edf-energy-eligibility.yml
source_heading: Eligibility
source_page: https://www.edfenergy.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EDF Energy\naid: edf-energy\nurl: https://www.edfenergy.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or reputation-damaging use\n  text: You must not use the Website for any illegal purpose or for any purpose that in our reasonable opinion damages\n    our reputation or the reputation of any of our Group Companies, customers, suppliers or other users.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Before you can access MyAccount or MyLearningHub you may be required to\
  \ complete a registration process\n    by providing the information requested by us.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/edf-energy/eligibility/edf-energy-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from EDF Energy's own page on 2026-11-09.
synthetic: false
tags:
- Energy
- United Kingdom
- Utilities
- Electricity
- Gas
- Energy Retailer
- Energy Supplier
- Smart Metering
- Nuclear
- Renewables
- EV Charging
- Demand Response
- Tariffs
- Energy Markets
---
