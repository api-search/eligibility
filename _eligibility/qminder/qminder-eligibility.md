---
api_specs:
- filename: qminder-appointments-api-openapi.yml
  format: yaml
  label: Qminder Appointments API
  slug: qminder-appointments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qminder/openapi/qminder-appointments-api-openapi.yml
- filename: qminder-input-fields-api-openapi.yml
  format: yaml
  label: Qminder Input Fields API
  slug: qminder-input-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qminder/openapi/qminder-input-fields-api-openapi.yml
- filename: qminder-lines-api-openapi.yml
  format: yaml
  label: Qminder Lines API
  slug: qminder-lines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qminder/openapi/qminder-lines-api-openapi.yml
- filename: qminder-locations-api-openapi.yml
  format: yaml
  label: Qminder Locations API
  slug: qminder-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qminder/openapi/qminder-locations-api-openapi.yml
- filename: qminder-tickets-api-openapi.yml
  format: yaml
  label: Qminder Tickets API
  slug: qminder-tickets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qminder/openapi/qminder-tickets-api-openapi.yml
- filename: qminder-users-api-openapi.yml
  format: yaml
  label: Qminder Users API
  slug: qminder-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qminder/openapi/qminder-users-api-openapi.yml
- filename: qminder-webhooks-api-openapi.yml
  format: yaml
  label: Qminder Webhooks API
  slug: qminder-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qminder/openapi/qminder-webhooks-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Data Location: all Client Data is stored and processed on secure servers located in the United States of America. Client must not be located in a country subject to U.S. Government embargo.'
  minimum_age:
    text: null
    value: null
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
name: Qminder
provenance_date: '2026-11-10'
provider_name: Qminder
provider_slug: qminder
slug: qminder-eligibility
source_date: '2026-11-10'
source_filename: qminder-eligibility.yml
source_heading: Eligibility
source_page: https://www.qminder.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Qminder\naid: qminder\nurl: https://www.qminder.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: 'Data Location: all Client Data is stored and processed on secure servers located in the United States of\n    America. Client must not be located in a country subject to U.S. Government embargo.'\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/qminder/eligibility/qminder-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Qminder's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Queue Management
- Appointment Scheduling
- Visitor Management
- Customer Experience
- REST
- GraphQL
- Webhook
- Software-as-a-Service
- Scheduling
---
