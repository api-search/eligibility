---
api_specs:
- filename: cello-events-api-openapi.yml
  format: yaml
  label: Cello Events API
  slug: cello-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cello/openapi/cello-events-api-openapi.yml
- filename: cello-new-users-api-openapi.yml
  format: yaml
  label: Cello New Users API
  slug: cello-new-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cello/openapi/cello-new-users-api-openapi.yml
- filename: cello-referral-codes-api-openapi.yml
  format: yaml
  label: Cello Referral Codes API
  slug: cello-referral-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cello/openapi/cello-referral-codes-api-openapi.yml
- filename: cello-referrers-api-openapi.yml
  format: yaml
  label: Cello Referrers API
  slug: cello-referrers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cello/openapi/cello-referrers-api-openapi.yml
- filename: cello-token-api-openapi.yml
  format: yaml
  label: Cello Token API
  slug: cello-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cello/openapi/cello-token-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Customers that are entrepreneurs (in terms of Sec. 14 German Civil Code (BGB)
    type: business
  - text: by Referral Users that may be entrepreneurs or consumers
    type: individual
  minimum_age:
    text: The Platform may only be accessed and used by Users who are of legal age and have full legal capacity
    value: legal age
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
name: Cello
provenance_date: '2026-11-09'
provider_name: Cello
provider_slug: cello
slug: cello-eligibility
source_date: '2026-11-09'
source_filename: cello-eligibility.yml
source_heading: Eligibility
source_page: https://cello.so/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cello\naid: cello\nurl: https://cello.so/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Customers that are entrepreneurs (in terms of Sec. 14 German Civil Code (BGB)\n- type: individual\n  text: by Referral Users that may be entrepreneurs or consumers\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: The Platform may only be accessed and used by Users who are of legal age and have full legal capacity\n"
source_yaml_url: https://artifacts.apis.io/cello/eligibility/cello-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Cello's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Referral Marketing
- Affiliate Marketing
- Growth
- Software-as-a-Service
- Attribution
- Partner Programs
- Ai Enterprise Software
- A2A
---
