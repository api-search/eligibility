---
api_specs:
- filename: volteras-accounts-api-openapi.yml
  format: yaml
  label: Volteras Accounts API
  slug: volteras-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volteras/openapi/volteras-accounts-api-openapi.yml
- filename: volteras-authentication-api-openapi.yml
  format: yaml
  label: Volteras Authentication API
  slug: volteras-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volteras/openapi/volteras-authentication-api-openapi.yml
- filename: volteras-rate-limit-api-openapi.yml
  format: yaml
  label: Volteras Rate Limit API
  slug: volteras-rate-limit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volteras/openapi/volteras-rate-limit-api-openapi.yml
- filename: volteras-tags-api-openapi.yml
  format: yaml
  label: Volteras Tags API
  slug: volteras-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volteras/openapi/volteras-tags-api-openapi.yml
- filename: volteras-vehicle-alerts-api-openapi.yml
  format: yaml
  label: Volteras Vehicle Alerts API
  slug: volteras-vehicle-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volteras/openapi/volteras-vehicle-alerts-api-openapi.yml
- filename: volteras-vehicle-charging-history-api-openapi.yml
  format: yaml
  label: Volteras Vehicle Charging History API
  slug: volteras-vehicle-charging-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volteras/openapi/volteras-vehicle-charging-history-api-openapi.yml
- filename: volteras-vehicle-charging-schedule-api-openapi.yml
  format: yaml
  label: Volteras Vehicle Charging Schedule API
  slug: volteras-vehicle-charging-schedule-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volteras/openapi/volteras-vehicle-charging-schedule-api-openapi.yml
- filename: volteras-vehicle-command-executions-api-openapi.yml
  format: yaml
  label: Volteras Vehicle Command Executions API
  slug: volteras-vehicle-command-executions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volteras/openapi/volteras-vehicle-command-executions-api-openapi.yml
- filename: volteras-vehicle-connection-api-openapi.yml
  format: yaml
  label: Volteras Vehicle Connection API
  slug: volteras-vehicle-connection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volteras/openapi/volteras-vehicle-connection-api-openapi.yml
- filename: volteras-vehicle-eligibility-api-openapi.yml
  format: yaml
  label: Volteras Vehicle Eligibility API
  slug: volteras-vehicle-eligibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volteras/openapi/volteras-vehicle-eligibility-api-openapi.yml
- filename: volteras-vehicle-journeys-api-openapi.yml
  format: yaml
  label: Volteras Vehicle Journeys API
  slug: volteras-vehicle-journeys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volteras/openapi/volteras-vehicle-journeys-api-openapi.yml
- filename: volteras-vehicle-listening-api-openapi.yml
  format: yaml
  label: Volteras Vehicle Listening API
  slug: volteras-vehicle-listening-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volteras/openapi/volteras-vehicle-listening-api-openapi.yml
- filename: volteras-vehicle-manufacturer-alerts-api-openapi.yml
  format: yaml
  label: Volteras Vehicle Manufacturer Alerts API
  slug: volteras-vehicle-manufacturer-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volteras/openapi/volteras-vehicle-manufacturer-alerts-api-openapi.yml
- filename: volteras-vehicle-range-api-openapi.yml
  format: yaml
  label: Volteras Vehicle Range API
  slug: volteras-vehicle-range-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volteras/openapi/volteras-vehicle-range-api-openapi.yml
- filename: volteras-vehicle-services-api-openapi.yml
  format: yaml
  label: Volteras Vehicle Services API
  slug: volteras-vehicle-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volteras/openapi/volteras-vehicle-services-api-openapi.yml
- filename: volteras-vehicle-state-of-health-api-openapi.yml
  format: yaml
  label: Volteras Vehicle State of Health API
  slug: volteras-vehicle-state-of-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volteras/openapi/volteras-vehicle-state-of-health-api-openapi.yml
- filename: volteras-vehicle-telemetry-api-openapi.yml
  format: yaml
  label: Volteras Vehicle Telemetry API
  slug: volteras-vehicle-telemetry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volteras/openapi/volteras-vehicle-telemetry-api-openapi.yml
- filename: volteras-vehicle-tires-api-openapi.yml
  format: yaml
  label: Volteras Vehicle Tires API
  slug: volteras-vehicle-tires-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volteras/openapi/volteras-vehicle-tires-api-openapi.yml
- filename: volteras-vehicles-api-openapi.yml
  format: yaml
  label: Volteras Vehicles API
  slug: volteras-vehicles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volteras/openapi/volteras-vehicles-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register an account to access certain features of our Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Volteras
provenance_date: '2026-11-10'
provider_name: Volteras
provider_slug: volteras
slug: volteras-eligibility
source_date: '2026-11-10'
source_filename: volteras-eligibility.yml
source_heading: Eligibility
source_page: https://www.volteras.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Volteras\naid: volteras\nurl: https://www.volteras.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to register an account to access certain features of our Services.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/volteras/eligibility/volteras-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from Volteras's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Electric Vehicles
- Connected Vehicles
- Automotive
- Vehicle Telemetry
- EV Charging
- Energy
- Mobility
- Fleet Management
- Telematics
---
