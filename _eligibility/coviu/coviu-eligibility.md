---
api_specs:
- filename: coviu-auth-api-openapi.yml
  format: yaml
  label: Coviu Auth API
  slug: coviu-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coviu/openapi/coviu-auth-api-openapi.yml
- filename: coviu-collections-api-openapi.yml
  format: yaml
  label: Coviu Collections API
  slug: coviu-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coviu/openapi/coviu-collections-api-openapi.yml
- filename: coviu-participants-api-openapi.yml
  format: yaml
  label: Coviu Participants API
  slug: coviu-participants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coviu/openapi/coviu-participants-api-openapi.yml
- filename: coviu-sessions-api-openapi.yml
  format: yaml
  label: Coviu Sessions API
  slug: coviu-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coviu/openapi/coviu-sessions-api-openapi.yml
- filename: coviu-waiting-area-api-openapi.yml
  format: yaml
  label: Coviu Waiting Area API
  slug: coviu-waiting-area-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coviu/openapi/coviu-waiting-area-api-openapi.yml
- filename: coviu-webhook-requests-api-openapi.yml
  format: yaml
  label: Coviu Webhook Requests API
  slug: coviu-webhook-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coviu/openapi/coviu-webhook-requests-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: These Service Terms between you (if you are an individual)
    type: individual
  - text: or your organization (if you are representing an organization)
    type: business
  minimum_age:
    text: If a user is under 18 years of age, he/she may not purchase any products or services through Coviu.
    value: '18'
  restricted_uses:
  - summary: Legal purposes only
    text: You are permitted to use the Coviu service only for legal purposes
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Coviu will strictly sell the Coviu Service through and with the approval of an adult user.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Coviu
provenance_date: '2026-11-09'
provider_name: Coviu
provider_slug: coviu
slug: coviu-eligibility
source_date: '2026-11-09'
source_filename: coviu-eligibility.yml
source_heading: Eligibility
source_page: https://www.coviu.com/en-us/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coviu\naid: coviu\nurl: https://www.coviu.com/en-us/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: These Service Terms between you (if you are an individual)\n- type: business\n  text: or your organization (if you are representing an organization)\nrestricted_uses:\n- summary: Legal purposes only\n  text: You are permitted to use the Coviu service only for legal purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Coviu will strictly sell the Coviu Service through and with the approval of an\
  \ adult user.\nminimum_age:\n  value: '18'\n  text: If a user is under 18 years of age, he/she may not purchase any products or services through Coviu.\n"
source_yaml_url: https://artifacts.apis.io/coviu/eligibility/coviu-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Coviu's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Telehealth
- Australia
- Virtual Care
- Video
- WebRTC
- Appointments
- Remote Monitoring
- REST
---
