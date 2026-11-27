---
api_specs:
- filename: capawesome-io-app-build-shares-api-openapi.yml
  format: yaml
  label: capawesome-io App Build Shares API
  slug: capawesome-io-app-build-shares-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capawesome-io/openapi/capawesome-io-app-build-shares-api-openapi.yml
- filename: capawesome-io-apps-api-openapi.yml
  format: yaml
  label: capawesome-io Apps API
  slug: capawesome-io-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capawesome-io/openapi/capawesome-io-apps-api-openapi.yml
- filename: capawesome-io-jobs-api-openapi.yml
  format: yaml
  label: capawesome-io Jobs API
  slug: capawesome-io-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capawesome-io/openapi/capawesome-io-jobs-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer and end users must not be domiciled in countries or regions subject to EU, UN, or US sanctions.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctions-restricted use
    text: The Customer warrants that neither it nor its end users are domiciled in countries or regions subject to EU, UN, or US sanctions and are not listed on any sanctions lists.
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
name: capawesome-io
provenance_date: '2026-11-09'
provider_name: capawesome-io
provider_slug: capawesome-io
slug: capawesome-io-eligibility
source_date: '2026-11-09'
source_filename: capawesome-io-eligibility.yml
source_heading: Eligibility
source_page: https://capawesome.io/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: capawesome-io\naid: capawesome-io\nurl: https://capawesome.io/legal/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer and end users must not be domiciled in countries or regions subject to EU, UN, or US sanctions.\nentity_types: []\nrestricted_uses:\n- summary: Sanctions-restricted use\n  text: The Customer warrants that neither it nor its end users are domiciled in countries or regions subject to\n    EU, UN, or US sanctions and are not listed on any sanctions lists.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/capawesome-io/eligibility/capawesome-io-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from capawesome-io's own page on 2026-11-09.
synthetic: false
tags:
- Mobile
- DevOps
- CI/CD
- OTA
- Capacitor
- Ionic
---
