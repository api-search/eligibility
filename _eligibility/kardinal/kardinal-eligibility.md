---
api_specs:
- filename: kardinal-plan-api-openapi.yml
  format: yaml
  label: Kardinal Plan API
  slug: kardinal-plan-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kardinal/openapi/kardinal-plan-api-openapi.yml
- filename: kardinal-solution-api-openapi.yml
  format: yaml
  label: Kardinal Solution API
  slug: kardinal-solution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kardinal/openapi/kardinal-solution-api-openapi.yml
- filename: kardinal-webhook-api-openapi.yml
  format: yaml
  label: Kardinal Webhook API
  slug: kardinal-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kardinal/openapi/kardinal-webhook-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The App is available via the Apple App Store and the Google Play Store, in the territories where these platforms distribute it.
  entity_types:
  - text: It is aimed at professionals (companies, self-employed individuals, sole traders) acting in the course of their business.
    type: business
  minimum_age:
    text: Access is reserved for professionals of legal age.
    value: legal age
  restricted_uses:
  - summary: Professional use only
    text: The App is intended exclusively for professional use.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Kardinal reserves the right to refuse or terminate access in the event of a manifestly inaccurate declaration.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Kardinal
provenance_date: '2026-11-09'
provider_name: Kardinal
provider_slug: kardinal
slug: kardinal-eligibility
source_date: '2026-11-09'
source_filename: kardinal-eligibility.yml
source_heading: Eligibility
source_page: https://kardinal.ai/terms-of-service-laskar/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kardinal\naid: kardinal\nurl: https://kardinal.ai/terms-of-service-laskar/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The App is available via the Apple App Store and the Google Play Store, in the territories where these platforms\n    distribute it.\nentity_types:\n- type: business\n  text: It is aimed at professionals (companies, self-employed individuals, sole traders) acting in the course of\n    their business.\nrestricted_uses:\n- summary: Professional use only\n  text: The App is intended exclusively for professional use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: Kardinal reserves the right to refuse or terminate access in the event of a manifestly inaccurate declaration.\nminimum_age:\n  value: legal age\n  text: Access is reserved for professionals of legal age.\n"
source_yaml_url: https://artifacts.apis.io/kardinal/eligibility/kardinal-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Kardinal's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Route Optimization
- Vehicle Routing
- Last Mile Delivery
- Logistics
- Supply Chain
- Transportation
- Fleet Management
- Optimization
- A2A
---
