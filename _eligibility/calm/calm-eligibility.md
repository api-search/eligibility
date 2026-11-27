---
api_specs:
- filename: calm-authentication-api-openapi.yml
  format: yaml
  label: Calm Authentication API
  slug: calm-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calm/openapi/calm-authentication-api-openapi.yml
- filename: calm-subscriptions-api-openapi.yml
  format: yaml
  label: Calm Subscriptions API
  slug: calm-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calm/openapi/calm-subscriptions-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 16 years or older to use the Services. If you are under the age of majority where you live, you may only use the Services if your parent or guardian agrees to our Terms.
    type: individual
  minimum_age:
    text: You must be 16 years or older to use the Services.
    value: '16'
  restricted_uses:
  - summary: Not for emergencies or crisis
    text: The Services, including any AI Features, are not designed for use in medical or mental health emergencies.
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
name: Calm
provenance_date: '2026-11-09'
provider_name: Calm
provider_slug: calm
slug: calm-eligibility
source_date: '2026-11-09'
source_filename: calm-eligibility.yml
source_heading: Eligibility
source_page: https://www.calm.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Calm\naid: calm\nurl: https://www.calm.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be 16 years or older to use the Services. If you are under the age of majority where you live,\n    you may only use the Services if your parent or guardian agrees to our Terms.\nrestricted_uses:\n- summary: Not for emergencies or crisis\n  text: The Services, including any AI Features, are not designed for use in medical or mental health emergencies.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be 16 years or older to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/calm/eligibility/calm-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Calm's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Mental Health
- Wellness
- Meditation
- Mindfulness
- Sleep
- Employee Benefits
- Health
- B2B
- Subscription
---
