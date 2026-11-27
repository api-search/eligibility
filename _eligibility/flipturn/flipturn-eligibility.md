---
api_specs:
- filename: flipturn-access-ids-api-openapi.yml
  format: yaml
  label: Flipturn Access IDs API
  slug: flipturn-access-ids-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flipturn/openapi/flipturn-access-ids-api-openapi.yml
- filename: flipturn-alerts-api-openapi.yml
  format: yaml
  label: Flipturn Alerts API
  slug: flipturn-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flipturn/openapi/flipturn-alerts-api-openapi.yml
- filename: flipturn-charger-health-api-openapi.yml
  format: yaml
  label: Flipturn Charger Health API
  slug: flipturn-charger-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flipturn/openapi/flipturn-charger-health-api-openapi.yml
- filename: flipturn-chargers-api-openapi.yml
  format: yaml
  label: Flipturn Chargers API
  slug: flipturn-chargers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flipturn/openapi/flipturn-chargers-api-openapi.yml
- filename: flipturn-charging-sessions-api-openapi.yml
  format: yaml
  label: Flipturn Charging Sessions API
  slug: flipturn-charging-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flipturn/openapi/flipturn-charging-sessions-api-openapi.yml
- filename: flipturn-departure-times-api-openapi.yml
  format: yaml
  label: Flipturn Departure Times API
  slug: flipturn-departure-times-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flipturn/openapi/flipturn-departure-times-api-openapi.yml
- filename: flipturn-errors-api-openapi.yml
  format: yaml
  label: Flipturn Errors API
  slug: flipturn-errors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flipturn/openapi/flipturn-errors-api-openapi.yml
- filename: flipturn-maintenance-windows-api-openapi.yml
  format: yaml
  label: Flipturn Maintenance Windows API
  slug: flipturn-maintenance-windows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flipturn/openapi/flipturn-maintenance-windows-api-openapi.yml
- filename: flipturn-ocpp-messages-api-openapi.yml
  format: yaml
  label: Flipturn OCPP Messages API
  slug: flipturn-ocpp-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flipturn/openapi/flipturn-ocpp-messages-api-openapi.yml
- filename: flipturn-reservations-api-openapi.yml
  format: yaml
  label: Flipturn Reservations API
  slug: flipturn-reservations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flipturn/openapi/flipturn-reservations-api-openapi.yml
- filename: flipturn-site-power-limits-api-openapi.yml
  format: yaml
  label: Flipturn Site Power Limits API
  slug: flipturn-site-power-limits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flipturn/openapi/flipturn-site-power-limits-api-openapi.yml
- filename: flipturn-sites-api-openapi.yml
  format: yaml
  label: Flipturn Sites API
  slug: flipturn-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flipturn/openapi/flipturn-sites-api-openapi.yml
- filename: flipturn-vehicles-api-openapi.yml
  format: yaml
  label: Flipturn Vehicles API
  slug: flipturn-vehicles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flipturn/openapi/flipturn-vehicles-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: (b) you are 18 years old or older
    value: '18'
  restricted_uses:
  - summary: High-risk activities
    text: the Services are not designed or intended for use in hazardous environments requiring fail safe performance
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
name: Flipturn
provenance_date: '2026-11-09'
provider_name: Flipturn
provider_slug: flipturn
slug: flipturn-eligibility
source_date: '2026-11-09'
source_filename: flipturn-eligibility.yml
source_heading: Eligibility
source_page: https://www.getflipturn.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Flipturn\naid: flipturn\nurl: https://www.getflipturn.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: High-risk activities\n  text: the Services are not designed or intended for use in hazardous environments requiring fail safe performance\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: (b) you are 18 years old or older\n"
source_yaml_url: https://artifacts.apis.io/flipturn/eligibility/flipturn-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Flipturn's own page on 2026-11-09.
synthetic: false
tags:
- Company
- EV Charging
- Electric Vehicles
- Fleet Management
- Energy
- Charging Infrastructure
- OCPP
- OCPI
- Mobility
- REST API
---
