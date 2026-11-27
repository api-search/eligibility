---
api_specs:
- filename: airthings-accounts-api-openapi.yml
  format: yaml
  label: Airthings Accounts API
  slug: airthings-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airthings/openapi/airthings-accounts-api-openapi.yml
- filename: airthings-device-api-openapi.yml
  format: yaml
  label: Airthings Device API
  slug: airthings-device-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airthings/openapi/airthings-device-api-openapi.yml
- filename: airthings-devices-api-openapi.yml
  format: yaml
  label: Airthings Devices API
  slug: airthings-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airthings/openapi/airthings-devices-api-openapi.yml
- filename: airthings-health-api-openapi.yml
  format: yaml
  label: Airthings Health API
  slug: airthings-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airthings/openapi/airthings-health-api-openapi.yml
- filename: airthings-locations-api-openapi.yml
  format: yaml
  label: Airthings Locations API
  slug: airthings-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airthings/openapi/airthings-locations-api-openapi.yml
- filename: airthings-organizations-api-openapi.yml
  format: yaml
  label: Airthings Organizations API
  slug: airthings-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airthings/openapi/airthings-organizations-api-openapi.yml
- filename: airthings-segments-api-openapi.yml
  format: yaml
  label: Airthings Segments API
  slug: airthings-segments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airthings/openapi/airthings-segments-api-openapi.yml
- filename: airthings-sensor-api-openapi.yml
  format: yaml
  label: Airthings Sensor API
  slug: airthings-sensor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airthings/openapi/airthings-sensor-api-openapi.yml
- filename: airthings-spaces-api-openapi.yml
  format: yaml
  label: Airthings Spaces API
  slug: airthings-spaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airthings/openapi/airthings-spaces-api-openapi.yml
- filename: airthings-thresholds-api-openapi.yml
  format: yaml
  label: Airthings Thresholds API
  slug: airthings-thresholds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airthings/openapi/airthings-thresholds-api-openapi.yml
- filename: airthings-webhooks-api-openapi.yml
  format: yaml
  label: Airthings Webhooks API
  slug: airthings-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airthings/openapi/airthings-webhooks-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are at least eighteen (18) years of age.
    type: individual
  - text: A “Partner” is generally a business and/or service professional that has sold a Product to a Customer
    type: business
  minimum_age:
    text: You represent and warrant that you are at least eighteen (18) years of age.
    value: '18'
  restricted_uses:
  - summary: Export to sanctioned countries
    text: The Partner shall not export or re-export any Products or Services subject to export and re-export laws to a government sanctioned country or any person listed on a government denied party list.
  - summary: Illegal or unauthorized purposes
    text: We specifically prohibit the use of our Services and/or Products for any illegal or unauthorized purpose
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Airthings may appoint the Partner as an independent, non-exclusive, authorized reseller of the Products and Subscriptions to Services in the Territory.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Airthings
provenance_date: '2026-11-09'
provider_name: Airthings
provider_slug: airthings
slug: airthings-eligibility
source_date: '2026-11-09'
source_filename: airthings-eligibility.yml
source_heading: Eligibility
source_page: https://www.airthings.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Airthings\naid: airthings\nurl: https://www.airthings.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are at least eighteen (18) years of age.\n- type: business\n  text: A “Partner” is generally a business and/or service professional that has sold a Product to a Customer\nrestricted_uses:\n- summary: Export to sanctioned countries\n  text: The Partner shall not export or re-export any Products or Services subject to export and re-export laws\n    to a government sanctioned country\
  \ or any person listed on a government denied party list.\n- summary: Illegal or unauthorized purposes\n  text: We specifically prohibit the use of our Services and/or Products for any illegal or unauthorized purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Airthings may appoint the Partner as an independent, non-exclusive, authorized reseller of the Products\n    and Subscriptions to Services in the Territory.\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are at least eighteen (18) years of age.\n"
source_yaml_url: https://artifacts.apis.io/airthings/eligibility/airthings-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Airthings's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Air Quality
- Radon
- Sensors
- IoT
---
