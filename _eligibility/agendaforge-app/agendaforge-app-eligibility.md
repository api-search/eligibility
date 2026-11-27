---
api_specs:
- filename: agendaforge-app-connection-api-openapi.yml
  format: yaml
  label: agendaforge-app Connection API
  slug: agendaforge-app-connection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agendaforge-app/openapi/agendaforge-app-connection-api-openapi.yml
- filename: agendaforge-app-jobs-api-openapi.yml
  format: yaml
  label: agendaforge-app Jobs API
  slug: agendaforge-app-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agendaforge-app/openapi/agendaforge-app-jobs-api-openapi.yml
- filename: agendaforge-app-records-api-openapi.yml
  format: yaml
  label: agendaforge-app Records API
  slug: agendaforge-app-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agendaforge-app/openapi/agendaforge-app-records-api-openapi.yml
- filename: agendaforge-app-webhooks-api-openapi.yml
  format: yaml
  label: agendaforge-app Webhooks API
  slug: agendaforge-app-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agendaforge-app/openapi/agendaforge-app-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 16 years old and able to form a binding contract to use the Service.
    value: '16'
  restricted_uses:
  - summary: Unlawful or abusive use
    text: Use the Service in violation of any applicable law or regulation.
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
name: agendaforge-app
provenance_date: '2026-11-09'
provider_name: agendaforge-app
provider_slug: agendaforge-app
slug: agendaforge-app-eligibility
source_date: '2026-11-09'
source_filename: agendaforge-app-eligibility.yml
source_heading: Eligibility
source_page: https://agendaforge.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: agendaforge-app\naid: agendaforge-app\nurl: https://agendaforge.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or abusive use\n  text: Use the Service in violation of any applicable law or regulation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old and able to form a binding contract to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/agendaforge-app/eligibility/agendaforge-app-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from agendaforge-app's own page on 2026-11-09.
synthetic: false
tags:
- Event Management
- Software-as-a-Service
- AI-native
- Conferences
- Software
---
