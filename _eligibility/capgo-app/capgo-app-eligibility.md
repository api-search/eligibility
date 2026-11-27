---
api_specs:
- filename: capgo-app-api-keys-api-openapi.yml
  format: yaml
  label: Capgo API Keys API
  slug: capgo-app-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capgo-app/openapi/capgo-app-api-keys-api-openapi.yml
- filename: capgo-app-apps-api-openapi.yml
  format: yaml
  label: Capgo Apps API
  slug: capgo-app-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capgo-app/openapi/capgo-app-apps-api-openapi.yml
- filename: capgo-app-bundles-api-openapi.yml
  format: yaml
  label: Capgo Bundles API
  slug: capgo-app-bundles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capgo-app/openapi/capgo-app-bundles-api-openapi.yml
- filename: capgo-app-channels-api-openapi.yml
  format: yaml
  label: Capgo Channels API
  slug: capgo-app-channels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capgo-app/openapi/capgo-app-channels-api-openapi.yml
- filename: capgo-app-devices-api-openapi.yml
  format: yaml
  label: Capgo Devices API
  slug: capgo-app-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capgo-app/openapi/capgo-app-devices-api-openapi.yml
- filename: capgo-app-members-api-openapi.yml
  format: yaml
  label: Capgo Members API
  slug: capgo-app-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capgo-app/openapi/capgo-app-members-api-openapi.yml
- filename: capgo-app-organizations-api-openapi.yml
  format: yaml
  label: Capgo Organizations API
  slug: capgo-app-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capgo-app/openapi/capgo-app-organizations-api-openapi.yml
- filename: capgo-app-statistics-api-openapi.yml
  format: yaml
  label: Capgo Statistics API
  slug: capgo-app-statistics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capgo-app/openapi/capgo-app-statistics-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You are not located in a country that is subject to the United States government embargo
  minimum_age:
    text: You represent that you are over the age of 18. The Company does not permit those under 18 to use the Service.
    value: '18'
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
name: Capgo
provenance_date: '2026-11-09'
provider_name: Capgo
provider_slug: capgo-app
slug: capgo-app-eligibility
source_date: '2026-11-09'
source_filename: capgo-app-eligibility.yml
source_heading: Eligibility
source_page: https://capgo.app/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Capgo\naid: capgo-app\nurl: https://capgo.app/tos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You are not located in a country that is subject to the United States government embargo\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are over the age of 18. The Company does not permit those under 18 to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/capgo-app/eligibility/capgo-app-eligibility.yml
stated_fields:
- countries
- minimum_age
summary_line: 2 quoted statements, read from Capgo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Mobile
- Development
- Capacitor
---
