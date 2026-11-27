---
api_specs:
- filename: loconav-alert-subscriptions-api-openapi.yml
  format: yaml
  label: LocoNav Alert Subscriptions API
  slug: loconav-alert-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loconav/openapi/loconav-alert-subscriptions-api-openapi.yml
- filename: loconav-alerts-api-openapi.yml
  format: yaml
  label: LocoNav Alerts API
  slug: loconav-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loconav/openapi/loconav-alerts-api-openapi.yml
- filename: loconav-alerts-subscriptions-api-openapi.yml
  format: yaml
  label: LocoNav Alerts Subscriptions API
  slug: loconav-alerts-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loconav/openapi/loconav-alerts-subscriptions-api-openapi.yml
- filename: loconav-drivers-api-openapi.yml
  format: yaml
  label: LocoNav Drivers API
  slug: loconav-drivers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loconav/openapi/loconav-drivers-api-openapi.yml
- filename: loconav-mobilization-api-openapi.yml
  format: yaml
  label: LocoNav Mobilization API
  slug: loconav-mobilization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loconav/openapi/loconav-mobilization-api-openapi.yml
- filename: loconav-polygon-geofence-api-openapi.yml
  format: yaml
  label: LocoNav Polygon (Geofence) API
  slug: loconav-polygon-geofence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loconav/openapi/loconav-polygon-geofence-api-openapi.yml
- filename: loconav-trips-api-openapi.yml
  format: yaml
  label: LocoNav Trips API
  slug: loconav-trips-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loconav/openapi/loconav-trips-api-openapi.yml
- filename: loconav-users-api-openapi.yml
  format: yaml
  label: LocoNav Users API
  slug: loconav-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loconav/openapi/loconav-users-api-openapi.yml
- filename: loconav-vehicles-api-openapi.yml
  format: yaml
  label: LocoNav Vehicles API
  slug: loconav-vehicles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loconav/openapi/loconav-vehicles-api-openapi.yml
- filename: loconav-vehicles-telematics-api-openapi.yml
  format: yaml
  label: LocoNav Vehicles / Telematics API
  slug: loconav-vehicles-telematics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loconav/openapi/loconav-vehicles-telematics-api-openapi.yml
- filename: loconav-video-telematics-vt-live-stream-api-openapi.yml
  format: yaml
  label: LocoNav Video Telematics VT / Live Stream API
  slug: loconav-video-telematics-vt-live-stream-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loconav/openapi/loconav-video-telematics-vt-live-stream-api-openapi.yml
- filename: loconav-video-telematics-vt-videos-api-openapi.yml
  format: yaml
  label: LocoNav Video Telematics VT / Videos API
  slug: loconav-video-telematics-vt-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loconav/openapi/loconav-video-telematics-vt-videos-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are registering as a business entity, you represent that you have the authority to bind your entity or your organisation to these Terms of Use.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful use
    text: You warrant to Platform Owner that you will not use the Platform for any purpose that is unlawful, illegal or prohibited by these Terms.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Such Users and their details shall be verified by the Platform Owner by a detailed process.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: LocoNav
provenance_date: '2026-11-09'
provider_name: LocoNav
provider_slug: loconav
slug: loconav-eligibility
source_date: '2026-11-09'
source_filename: loconav-eligibility.yml
source_heading: Eligibility
source_page: https://loconav.com/termsofuse
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LocoNav\naid: loconav\nurl: https://loconav.com/termsofuse\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are registering as a business entity, you represent that you have the authority to bind your entity\n    or your organisation to these Terms of Use.\nrestricted_uses:\n- summary: Unlawful use\n  text: You warrant to Platform Owner that you will not use the Platform for any purpose that is unlawful, illegal\n    or prohibited by these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Such\
  \ Users and their details shall be verified by the Platform Owner by a detailed process.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/loconav/eligibility/loconav-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from LocoNav's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fleet Management
- Telematics
- GPS Tracking
- Vehicle Tracking
- Transportation
- Logistics
- IoT
- Video Telematics
- Webhook
---
