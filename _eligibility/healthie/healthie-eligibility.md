---
api_specs:
- filename: healthie-webhooks-asyncapi.yml
  format: yaml
  label: Healthie GraphQL API
  slug: healthie-graphql-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/healthie/asyncapi/healthie-webhooks-asyncapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Children under the age of 13 are not permitted to use the Services.
    value: '13'
  restricted_uses:
  - summary: Unlawful or fraudulent use
    text: may not use the Services to engage in any unlawful activity or fraudulent purpose
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
name: Healthie
provenance_date: '2026-11-09'
provider_name: Healthie
provider_slug: healthie
slug: healthie-eligibility
source_date: '2026-11-09'
source_filename: healthie-eligibility.yml
source_heading: Eligibility
source_page: https://www.gethealthie.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Healthie\naid: healthie\nurl: https://www.gethealthie.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or fraudulent use\n  text: may not use the Services to engage in any unlawful activity or fraudulent purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Children under the age of 13 are not permitted to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/healthie/eligibility/healthie-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Healthie's own page on 2026-11-09.
synthetic: false
tags:
- API-First
- Appointments
- Billing
- Care Plans
- Charting
- Claims
- Clinical
- Digital Health
- Electronic Health Records
- Forms
- GraphQL
- Health Tech
- Healthcare
- Insurance
- Intake
- Online Programs
- Patient Engagement
- Patient Portal
- Practice Management
- Programs
- Scheduling
- Telehealth
- Wellness
- Webhook
- Real-Time
- FHIR
---
