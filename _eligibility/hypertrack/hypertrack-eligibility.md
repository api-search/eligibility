---
api_specs:
- filename: hypertrack-authentication-api-openapi.yml
  format: yaml
  label: HyperTrack Authentication API
  slug: hypertrack-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hypertrack/openapi/hypertrack-authentication-api-openapi.yml
- filename: hypertrack-export-api-openapi.yml
  format: yaml
  label: HyperTrack Export API
  slug: hypertrack-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hypertrack/openapi/hypertrack-export-api-openapi.yml
- filename: hypertrack-geotags-api-openapi.yml
  format: yaml
  label: HyperTrack Geotags API
  slug: hypertrack-geotags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hypertrack/openapi/hypertrack-geotags-api-openapi.yml
- filename: hypertrack-nearby-api-openapi.yml
  format: yaml
  label: HyperTrack Nearby API
  slug: hypertrack-nearby-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hypertrack/openapi/hypertrack-nearby-api-openapi.yml
- filename: hypertrack-orders-api-openapi.yml
  format: yaml
  label: HyperTrack Orders API
  slug: hypertrack-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hypertrack/openapi/hypertrack-orders-api-openapi.yml
- filename: hypertrack-places-api-openapi.yml
  format: yaml
  label: HyperTrack Places API
  slug: hypertrack-places-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hypertrack/openapi/hypertrack-places-api-openapi.yml
- filename: hypertrack-tracking-api-openapi.yml
  format: yaml
  label: HyperTrack Tracking API
  slug: hypertrack-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hypertrack/openapi/hypertrack-tracking-api-openapi.yml
- filename: hypertrack-visits-api-openapi.yml
  format: yaml
  label: HyperTrack Visits API
  slug: hypertrack-visits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hypertrack/openapi/hypertrack-visits-api-openapi.yml
- filename: hypertrack-workerexport-api-openapi.yml
  format: yaml
  label: HyperTrack Worker Export API
  slug: hypertrack-workerexport-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hypertrack/openapi/hypertrack-workerexport-api-openapi.yml
- filename: hypertrack-workers-api-openapi.yml
  format: yaml
  label: HyperTrack Workers API
  slug: hypertrack-workers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hypertrack/openapi/hypertrack-workers-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Services only if you are or 13 years or older and are not barred from using the Services under applicable law.
    type: individual
  - text: If you are accessing and using the Services on behalf of a company (such as your employer) or other legal entity, you represent and warrant that you have the authority to bind that company or other legal entity to these Terms.
    type: business
  minimum_age:
    text: You may use the Services only if you are or 13 years or older
    value: '13'
  restricted_uses:
  - summary: Marketing messages without consent
    text: You will not send marketing messages without prior express written consent
  - summary: Commercial purpose use
    text: Use the Services or Content, or any portion thereof, for any commercial purpose
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
name: HyperTrack
provenance_date: '2026-11-09'
provider_name: HyperTrack
provider_slug: hypertrack
slug: hypertrack-eligibility
source_date: '2026-11-09'
source_filename: hypertrack-eligibility.yml
source_heading: Eligibility
source_page: https://hypertrack.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HyperTrack\naid: hypertrack\nurl: https://hypertrack.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Services only if you are or 13 years or older and are not barred from using the Services\n    under applicable law.\n- type: business\n  text: If you are accessing and using the Services on behalf of a company (such as your employer) or other legal\n    entity, you represent and warrant that you have the authority to bind that company or other legal entity to\n    these Terms.\nrestricted_uses:\n- summary:\
  \ Marketing messages without consent\n  text: You will not send marketing messages without prior express written consent\n- summary: Commercial purpose use\n  text: Use the Services or Content, or any portion thereof, for any commercial purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You may use the Services only if you are or 13 years or older\n"
source_yaml_url: https://artifacts.apis.io/hypertrack/eligibility/hypertrack-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from HyperTrack's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Location
- Geolocation
- Tracking
- Logistics
- Last Mile Delivery
- Field Service Management
- Workforce
- Time and Attendance
- Mobile SDK
- Geofencing
- Routing
---
