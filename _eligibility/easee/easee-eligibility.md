---
api_specs:
- filename: easee-account-api-openapi.yml
  format: yaml
  label: Easee Account API
  slug: easee-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-account-api-openapi.yml
- filename: easee-authorizecharging-api-openapi.yml
  format: yaml
  label: Easee Authorize Charging API
  slug: easee-authorizecharging-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-authorizecharging-api-openapi.yml
- filename: easee-charge-session-api-openapi.yml
  format: yaml
  label: Easee Charge Session API
  slug: easee-charge-session-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-charge-session-api-openapi.yml
- filename: easee-charger-api-openapi.yml
  format: yaml
  label: Easee Charger API
  slug: easee-charger-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-charger-api-openapi.yml
- filename: easee-cloud-ocpp-api-openapi.yml
  format: yaml
  label: Easee Cloud OCPP API
  slug: easee-cloud-ocpp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-cloud-ocpp-api-openapi.yml
- filename: easee-daily-schedule-api-openapi.yml
  format: yaml
  label: Easee Daily schedule API
  slug: easee-daily-schedule-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-daily-schedule-api-openapi.yml
- filename: easee-delayed-schedule-api-openapi.yml
  format: yaml
  label: Easee Delayed schedule API
  slug: easee-delayed-schedule-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-delayed-schedule-api-openapi.yml
- filename: easee-direct-ocpp-for-operators-api-openapi.yml
  format: yaml
  label: Easee Direct OCPP - For Operators API
  slug: easee-direct-ocpp-for-operators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-direct-ocpp-for-operators-api-openapi.yml
- filename: easee-direct-ocpp-for-users-api-openapi.yml
  format: yaml
  label: Easee Direct OCPP - For Users API
  slug: easee-direct-ocpp-for-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-direct-ocpp-for-users-api-openapi.yml
- filename: easee-easeekeys-api-openapi.yml
  format: yaml
  label: Easee Easee Keys API
  slug: easee-easeekeys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-easeekeys-api-openapi.yml
- filename: easee-energy-reporting-api-openapi.yml
  format: yaml
  label: Easee Energy Reporting API
  slug: easee-energy-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-energy-reporting-api-openapi.yml
- filename: easee-equalizer-api-openapi.yml
  format: yaml
  label: Easee Equalizer API
  slug: easee-equalizer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-equalizer-api-openapi.yml
- filename: easee-observations-api-openapi.yml
  format: yaml
  label: Easee Observations API
  slug: easee-observations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-observations-api-openapi.yml
- filename: easee-resources-api-openapi.yml
  format: yaml
  label: Easee Resources API
  slug: easee-resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-resources-api-openapi.yml
- filename: easee-site-api-openapi.yml
  format: yaml
  label: Easee Site API
  slug: easee-site-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-site-api-openapi.yml
- filename: easee-site-charge-session-api-openapi.yml
  format: yaml
  label: Easee Site Charge Session API
  slug: easee-site-charge-session-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-site-charge-session-api-openapi.yml
- filename: easee-state-api-openapi.yml
  format: yaml
  label: Easee State API
  slug: easee-state-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-state-api-openapi.yml
- filename: easee-weekly-schedule-api-openapi.yml
  format: yaml
  label: Easee Weekly schedule API
  slug: easee-weekly-schedule-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-weekly-schedule-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: By downloading and Installing the Easee Apps or creating an account in our website, you confirm that you are over 18 years of age
    value: '18'
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
name: Easee
provenance_date: '2026-11-09'
provider_name: Easee
provider_slug: easee
slug: easee-eligibility
source_date: '2026-11-09'
source_filename: easee-eligibility.yml
source_heading: Eligibility
source_page: https://easee.com/en/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Easee\naid: easee\nurl: https://easee.com/en/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By downloading and Installing the Easee Apps or creating an account in our website, you confirm that you\n    are over 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/easee/eligibility/easee-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from Easee's own page on 2026-11-09.
synthetic: false
tags:
- Company
- EV Charging
- Smart Home
- IoT
- Energy
---
