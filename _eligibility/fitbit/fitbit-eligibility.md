---
api_specs:
- filename: fitbit-user-api-openapi.yml
  format: yaml
  label: Fitbit User API
  slug: fitbit-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fitbit/openapi/fitbit-user-api-openapi.yml
- filename: fitbit-foods-api-openapi.yml
  format: yaml
  label: Fitbit Foods API
  slug: fitbit-foods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fitbit/openapi/fitbit-foods-api-openapi.yml
- filename: fitbit-oauth2-api-openapi.yml
  format: yaml
  label: Fitbit Oauth2 API
  slug: fitbit-oauth2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fitbit/openapi/fitbit-oauth2-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you do not have an account, you accept these Terms by using any part of the Fitbit Service.
    type: individual
  minimum_age:
    text: Persons under the age of 13, or any higher minimum age in the jurisdiction where that person resides, are not permitted to access or use the Fitbit Service unless their parent has consented in accordance with applicable law.
    value: '13'
  restricted_uses:
  - summary: Unauthorized devices or connections
    text: You may not connect to the Fitbit Service with any device that is not manufactured, distributed, or sold by Fitbit itself or through its authorized resellers or agents
  - source: https://dev.fitbit.com/legal/platform-terms-of-service/
    summary: High-risk and regulated uses
    text: any use of your Developer Application for a High-Risk Activity (as defined below). For each of the use cases described in items (1) - (3), you must collect informed consent from each User
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
name: Fitbit
provenance_date: '2026-11-09'
provider_name: Fitbit
provider_slug: fitbit
slug: fitbit-eligibility
source_date: '2026-11-09'
source_filename: fitbit-eligibility.yml
source_heading: Eligibility
source_page: https://support.google.com:443/product-documentation/answer/14816019
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fitbit\naid: fitbit\nurl: https://support.google.com:443/product-documentation/answer/14816019\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://dev.fitbit.com/legal/platform-terms-of-service/\n  - https://support.google.com:443/product-documentation/answer/14816019\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you do not have an account, you accept these Terms by using any part of the Fitbit Service.\nrestricted_uses:\n- summary: Unauthorized devices or connections\n  text: You may not connect to the Fitbit Service with any device that is not manufactured,\
  \ distributed, or sold\n    by Fitbit itself or through its authorized resellers or agents\n- summary: High-risk and regulated uses\n  text: any use of your Developer Application for a High-Risk Activity (as defined below). For each of the use cases\n    described in items (1) - (3), you must collect informed consent from each User\n  source: https://dev.fitbit.com/legal/platform-terms-of-service/\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Persons under the age of 13, or any higher minimum age in the jurisdiction where that person resides, are\n    not permitted to access or use the Fitbit Service unless their parent has consented in accordance with applicable\n    law.\n"
source_yaml_url: https://artifacts.apis.io/fitbit/eligibility/fitbit-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Fitbit's own page on 2026-11-09.
synthetic: false
tags:
- Wearables
- Health
- Fitness
- Activity Tracking
- Heart Rate
- Sleep
- Google
- IoT
- Wellness
---
