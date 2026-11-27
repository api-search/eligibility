---
api_specs:
- filename: thinair-co-account-api-openapi.yml
  format: yaml
  label: thinair-co Account API
  slug: thinair-co-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thinair-co/openapi/thinair-co-account-api-openapi.yml
- filename: thinair-co-billing-api-openapi.yml
  format: yaml
  label: thinair-co Billing API
  slug: thinair-co-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thinair-co/openapi/thinair-co-billing-api-openapi.yml
- filename: thinair-co-conditions-api-openapi.yml
  format: yaml
  label: thinair-co Conditions API
  slug: thinair-co-conditions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thinair-co/openapi/thinair-co-conditions-api-openapi.yml
- filename: thinair-co-connections-api-openapi.yml
  format: yaml
  label: thinair-co Connections API
  slug: thinair-co-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thinair-co/openapi/thinair-co-connections-api-openapi.yml
- filename: thinair-co-geocoding-api-openapi.yml
  format: yaml
  label: thinair-co Geocoding API
  slug: thinair-co-geocoding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thinair-co/openapi/thinair-co-geocoding-api-openapi.yml
- filename: thinair-co-geofences-api-openapi.yml
  format: yaml
  label: thinair-co Geofences API
  slug: thinair-co-geofences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thinair-co/openapi/thinair-co-geofences-api-openapi.yml
- filename: thinair-co-intersections-api-openapi.yml
  format: yaml
  label: thinair-co Intersections API
  slug: thinair-co-intersections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thinair-co/openapi/thinair-co-intersections-api-openapi.yml
- filename: thinair-co-learning-api-openapi.yml
  format: yaml
  label: thinair-co Learning API
  slug: thinair-co-learning-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thinair-co/openapi/thinair-co-learning-api-openapi.yml
- filename: thinair-co-migrations-api-openapi.yml
  format: yaml
  label: thinair-co Migrations API
  slug: thinair-co-migrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thinair-co/openapi/thinair-co-migrations-api-openapi.yml
- filename: thinair-co-places-api-openapi.yml
  format: yaml
  label: thinair-co Places API
  slug: thinair-co-places-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thinair-co/openapi/thinair-co-places-api-openapi.yml
- filename: thinair-co-query-api-openapi.yml
  format: yaml
  label: thinair-co Query API
  slug: thinair-co-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thinair-co/openapi/thinair-co-query-api-openapi.yml
- filename: thinair-co-routing-api-openapi.yml
  format: yaml
  label: thinair-co Routing API
  slug: thinair-co-routing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thinair-co/openapi/thinair-co-routing-api-openapi.yml
- filename: thinair-co-tables-api-openapi.yml
  format: yaml
  label: thinair-co Tables API
  slug: thinair-co-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thinair-co/openapi/thinair-co-tables-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: '"Territory" means the United States of America, or such other designated area approved by ThinAir applicable to your Services. Returns are available within the United States and Canada.'
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No tracking without permission
    text: Track and/or Monitor any individual without such individual’s prior express and legal permission unless such individual is a minor with whom You have a lawful guardian relationship
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You shall cooperate with the timely completion of the credit application provided by ThinAir for purposes of establishing a credit limit for outstanding invoices if you purchased the Services from ThinAir.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: thinair-co
provenance_date: '2026-11-10'
provider_name: thinair-co
provider_slug: thinair-co
slug: thinair-co-eligibility
source_date: '2026-11-10'
source_filename: thinair-co-eligibility.yml
source_heading: Eligibility
source_page: https://www.thinair.co/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: thinair-co\naid: thinair-co\nurl: https://www.thinair.co/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: '\"Territory\" means the United States of America, or such other designated area approved by ThinAir applicable\n    to your Services. Returns are available within the United States and Canada.'\nentity_types: []\nrestricted_uses:\n- summary: No tracking without permission\n  text: Track and/or Monitor any individual without such individual’s prior express and legal permission unless\n    such individual is a minor with whom You have a lawful guardian relationship\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You shall cooperate with the timely completion of the credit application provided by ThinAir for purposes\n    of establishing a credit limit for outstanding invoices if you purchased the Services from ThinAir.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/thinair-co/eligibility/thinair-co-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from thinair-co's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fleet Management
- Telematics
- Logistics
- Compliance
---
