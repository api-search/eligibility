---
api_specs:
- filename: fleetsu-accounts-api-openapi.yml
  format: yaml
  label: Fleetsu Accounts API
  slug: fleetsu-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fleetsu/openapi/fleetsu-accounts-api-openapi.yml
- filename: fleetsu-assets-api-openapi.yml
  format: yaml
  label: Fleetsu Assets API
  slug: fleetsu-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fleetsu/openapi/fleetsu-assets-api-openapi.yml
- filename: fleetsu-devices-api-openapi.yml
  format: yaml
  label: Fleetsu Devices API
  slug: fleetsu-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fleetsu/openapi/fleetsu-devices-api-openapi.yml
- filename: fleetsu-driver-api-openapi.yml
  format: yaml
  label: Fleetsu Driver API
  slug: fleetsu-driver-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fleetsu/openapi/fleetsu-driver-api-openapi.yml
- filename: fleetsu-events-api-openapi.yml
  format: yaml
  label: Fleetsu Events API
  slug: fleetsu-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fleetsu/openapi/fleetsu-events-api-openapi.yml
- filename: fleetsu-faults-api-openapi.yml
  format: yaml
  label: Fleetsu Faults API
  slug: fleetsu-faults-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fleetsu/openapi/fleetsu-faults-api-openapi.yml
- filename: fleetsu-fences-api-openapi.yml
  format: yaml
  label: Fleetsu Fences API
  slug: fleetsu-fences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fleetsu/openapi/fleetsu-fences-api-openapi.yml
- filename: fleetsu-general-api-openapi.yml
  format: yaml
  label: Fleetsu General API
  slug: fleetsu-general-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fleetsu/openapi/fleetsu-general-api-openapi.yml
- filename: fleetsu-groups-api-openapi.yml
  format: yaml
  label: Fleetsu Groups API
  slug: fleetsu-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fleetsu/openapi/fleetsu-groups-api-openapi.yml
- filename: fleetsu-installs-api-openapi.yml
  format: yaml
  label: Fleetsu Installs API
  slug: fleetsu-installs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fleetsu/openapi/fleetsu-installs-api-openapi.yml
- filename: fleetsu-kpi-api-openapi.yml
  format: yaml
  label: Fleetsu KPI API
  slug: fleetsu-kpi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fleetsu/openapi/fleetsu-kpi-api-openapi.yml
- filename: fleetsu-logbooks-api-openapi.yml
  format: yaml
  label: Fleetsu Logbooks API
  slug: fleetsu-logbooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fleetsu/openapi/fleetsu-logbooks-api-openapi.yml
- filename: fleetsu-maps-api-openapi.yml
  format: yaml
  label: Fleetsu Maps API
  slug: fleetsu-maps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fleetsu/openapi/fleetsu-maps-api-openapi.yml
- filename: fleetsu-reports-api-openapi.yml
  format: yaml
  label: Fleetsu Reports API
  slug: fleetsu-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fleetsu/openapi/fleetsu-reports-api-openapi.yml
- filename: fleetsu-subscriptions-api-openapi.yml
  format: yaml
  label: Fleetsu Subscriptions API
  slug: fleetsu-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fleetsu/openapi/fleetsu-subscriptions-api-openapi.yml
- filename: fleetsu-tags-api-openapi.yml
  format: yaml
  label: Fleetsu Tags API
  slug: fleetsu-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fleetsu/openapi/fleetsu-tags-api-openapi.yml
- filename: fleetsu-trips-api-openapi.yml
  format: yaml
  label: Fleetsu Trips API
  slug: fleetsu-trips-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fleetsu/openapi/fleetsu-trips-api-openapi.yml
- filename: fleetsu-user-api-openapi.yml
  format: yaml
  label: Fleetsu User API
  slug: fleetsu-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fleetsu/openapi/fleetsu-user-api-openapi.yml
- filename: fleetsu-users-api-openapi.yml
  format: yaml
  label: Fleetsu Users API
  slug: fleetsu-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fleetsu/openapi/fleetsu-users-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Products and Fleetsu Service are intended for use around the world.
  entity_types:
  - text: “Customer” means the entity identified as the customer in the Order Form.
    type: business
  minimum_age:
    text: You must be over 18 years of age to use or to purchase any Fleetsu Service or Products.
    value: '18'
  restricted_uses:
  - summary: No illegal tracking of persons
    text: must not use the Products or Fleetsu Service to illegally track or monitor any person without consent
  - summary: No emergency use
    text: the Products and Fleetsu Service are not failsafe and are not to be used for emergency use where failure of the Products or Fleetsu Service or inaccurate location information could lead to property damage, personal injury or death
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
name: Fleetsu
provenance_date: '2026-11-09'
provider_name: Fleetsu
provider_slug: fleetsu
slug: fleetsu-eligibility
source_date: '2026-11-09'
source_filename: fleetsu-eligibility.yml
source_heading: Eligibility
source_page: https://fleetsu.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fleetsu\naid: fleetsu\nurl: https://fleetsu.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Products and Fleetsu Service are intended for use around the world.\nentity_types:\n- type: business\n  text: “Customer” means the entity identified as the customer in the Order Form.\nrestricted_uses:\n- summary: No illegal tracking of persons\n  text: must not use the Products or Fleetsu Service to illegally track or monitor any person without consent\n- summary: No emergency use\n  text: the Products and Fleetsu Service are not failsafe and are not to be used for\
  \ emergency use where failure\n    of the Products or Fleetsu Service or inaccurate location information could lead to property damage, personal\n    injury or death\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be over 18 years of age to use or to purchase any Fleetsu Service or Products.\n"
source_yaml_url: https://artifacts.apis.io/fleetsu/eligibility/fleetsu-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Fleetsu's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fleet Management
- Telematics
- GPS Tracking
- Connected Vehicles
- Logistics
- Driver Safety
- Australia
---
