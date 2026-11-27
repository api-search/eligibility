---
api_specs:
- filename: clearspeed-clearspeed-integration-api-api-openapi.yml
  format: yaml
  label: Clearspeed Clearspeed Integration API
  slug: clearspeed-clearspeed-integration-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearspeed/openapi/clearspeed-clearspeed-integration-api-api-openapi.yml
- filename: clearspeed-participant-api-openapi.yml
  format: yaml
  label: Clearspeed Participant API
  slug: clearspeed-participant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearspeed/openapi/clearspeed-participant-api-openapi.yml
- filename: clearspeed-tenants-api-openapi.yml
  format: yaml
  label: Clearspeed Tenants API
  slug: clearspeed-tenants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearspeed/openapi/clearspeed-tenants-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Export clause: shall not be exported or transferred to any end-user located in a country embargoed by the United States'
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not a diagnostic opinion on honesty
    text: expressly should not be used for the purpose of rendering a diagnostic opinion regarding the honesty or dishonesty of an individual
  - summary: Participants must use natural human voices
    text: ensure that Participants only use natural human voices rather than any type of recorded, or any other form of altered, synthetic or computer-generated voice recordings and/or simulations
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
name: Clearspeed
provenance_date: '2026-11-09'
provider_name: Clearspeed
provider_slug: clearspeed
slug: clearspeed-eligibility
source_date: '2026-11-09'
source_filename: clearspeed-eligibility.yml
source_heading: Eligibility
source_page: https://www.clearspeed.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clearspeed\naid: clearspeed\nurl: https://www.clearspeed.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: 'Export clause: shall not be exported or transferred to any end-user located in a country embargoed by the\n    United States'\nentity_types: []\nrestricted_uses:\n- summary: Not a diagnostic opinion on honesty\n  text: expressly should not be used for the purpose of rendering a diagnostic opinion regarding the honesty or\n    dishonesty of an individual\n- summary: Participants must use natural human voices\n  text: ensure that Participants\
  \ only use natural human voices rather than any type of recorded, or any other form\n    of altered, synthetic or computer-generated voice recordings and/or simulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/clearspeed/eligibility/clearspeed-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from Clearspeed's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Risk Assessment
- Fraud Prevention
- Voice Analytics
- Artificial Intelligence
- Insurance
- Identity Verification
- Screening
- Security
---
