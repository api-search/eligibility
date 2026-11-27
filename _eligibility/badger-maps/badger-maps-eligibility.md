---
api_specs:
- filename: badger-maps-accounts-api-openapi.yml
  format: yaml
  label: Badger Maps Accounts API
  slug: badger-maps-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/badger-maps/openapi/badger-maps-accounts-api-openapi.yml
- filename: badger-maps-check-ins-api-openapi.yml
  format: yaml
  label: Badger Maps Check-Ins API
  slug: badger-maps-check-ins-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/badger-maps/openapi/badger-maps-check-ins-api-openapi.yml
- filename: badger-maps-locations-api-openapi.yml
  format: yaml
  label: Badger Maps Locations API
  slug: badger-maps-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/badger-maps/openapi/badger-maps-locations-api-openapi.yml
- filename: badger-maps-routes-api-openapi.yml
  format: yaml
  label: Badger Maps Routes API
  slug: badger-maps-routes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/badger-maps/openapi/badger-maps-routes-api-openapi.yml
- filename: badger-maps-users-api-openapi.yml
  format: yaml
  label: Badger Maps Users API
  slug: badger-maps-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/badger-maps/openapi/badger-maps-users-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: By agreeing to this Agreement, you represent and warrant to us that ... you are not located in a country that is subject to a U.S. government embargo
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not for high-risk activities
    text: THE SERVICES ARE NOT DESIGNED, MANUFACTURED, OR INTENDED FOR HIGH-RISK ACTIVITIES SUCH AS THE OPERATION OF EMERGENCY SERVICE, NUCLEAR FACILITIES, AIR TRAFFIC CONTROL OR LIFE SUPPORT SYSTEMS
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
name: Badger Maps
provenance_date: '2026-11-09'
provider_name: Badger Maps
provider_slug: badger-maps
slug: badger-maps-eligibility
source_date: '2026-11-09'
source_filename: badger-maps-eligibility.yml
source_heading: Eligibility
source_page: https://www.badgermapping.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Badger Maps\naid: badger-maps\nurl: https://www.badgermapping.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: By agreeing to this Agreement, you represent and warrant to us that ... you are not located in a country\n    that is subject to a U.S. government embargo\nentity_types: []\nrestricted_uses:\n- summary: Not for high-risk activities\n  text: THE SERVICES ARE NOT DESIGNED, MANUFACTURED, OR INTENDED FOR HIGH-RISK ACTIVITIES SUCH AS THE OPERATION\n    OF EMERGENCY SERVICE, NUCLEAR FACILITIES, AIR TRAFFIC CONTROL OR LIFE SUPPORT SYSTEMS\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/badger-maps/eligibility/badger-maps-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Badger Maps's own page on 2026-11-09.
synthetic: false
tags:
- Field Sales
- Route Planning
- Mapping
- CRM
- Sales Enablement
- Territory Management
---
