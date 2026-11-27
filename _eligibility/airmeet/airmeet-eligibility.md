---
api_specs:
- filename: airmeet-authentication-api-openapi.yml
  format: yaml
  label: Airmeet Authentication API
  slug: airmeet-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airmeet/openapi/airmeet-authentication-api-openapi.yml
- filename: airmeet-event-details-api-openapi.yml
  format: yaml
  label: Airmeet Event Details API
  slug: airmeet-event-details-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airmeet/openapi/airmeet-event-details-api-openapi.yml
- filename: airmeet-manage-event-api-openapi.yml
  format: yaml
  label: Airmeet Manage Event API
  slug: airmeet-manage-event-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airmeet/openapi/airmeet-manage-event-api-openapi.yml
- filename: airmeet-manage-event-series-api-openapi.yml
  format: yaml
  label: Airmeet Manage Event Series API
  slug: airmeet-manage-event-series-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airmeet/openapi/airmeet-manage-event-series-api-openapi.yml
- filename: airmeet-manage-registrations-api-openapi.yml
  format: yaml
  label: Airmeet Manage Registrations API
  slug: airmeet-manage-registrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airmeet/openapi/airmeet-manage-registrations-api-openapi.yml
- filename: airmeet-webhooks-api-openapi.yml
  format: yaml
  label: Airmeet Webhooks API
  slug: airmeet-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airmeet/openapi/airmeet-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You represent and warrant that You are a person of legal age to form a binding contract, in accordance with the applicable laws of the territory/country from where You are accessing the Platform.
    value: legal age to form a binding contract
  restricted_uses:
  - summary: Conduct and content limits
    text: shall not conduct Yourself in any manner which is immoral, unlawful and/or hurts or impacts other Users of the Platform.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to access the Services on the Platform, Hosts will have to register on the Platform by providing details as may be required by Airmeet
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Airmeet
provenance_date: '2026-11-09'
provider_name: Airmeet
provider_slug: airmeet
slug: airmeet-eligibility
source_date: '2026-11-09'
source_filename: airmeet-eligibility.yml
source_heading: Eligibility
source_page: https://www.airmeet.com/hub/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Airmeet\naid: airmeet\nurl: https://www.airmeet.com/hub/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Conduct and content limits\n  text: shall not conduct Yourself in any manner which is immoral, unlawful and/or hurts or impacts other Users\n    of the Platform.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to access the Services on the Platform, Hosts will have to register on the Platform by providing\n    details as may be required by Airmeet\nminimum_age:\n  value: legal\
  \ age to form a binding contract\n  text: You represent and warrant that You are a person of legal age to form a binding contract, in accordance with\n    the applicable laws of the territory/country from where You are accessing the Platform.\n"
source_yaml_url: https://artifacts.apis.io/airmeet/eligibility/airmeet-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Airmeet's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cloud Saas
- Event
- Virtual Events
- Webinars
- Event Management
- Community
- Webhook
---
