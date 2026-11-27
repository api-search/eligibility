---
api_specs:
- filename: acall-event-api-api-openapi.yml
  format: yaml
  label: Acall Event API
  slug: acall-event-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acall/openapi/acall-event-api-api-openapi.yml
- filename: acall-facility-api-api-openapi.yml
  format: yaml
  label: Acall Facility API
  slug: acall-facility-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acall/openapi/acall-facility-api-api-openapi.yml
- filename: acall-gate-api-api-openapi.yml
  format: yaml
  label: Acall Gate API
  slug: acall-gate-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acall/openapi/acall-gate-api-api-openapi.yml
- filename: acall-spot-api-api-openapi.yml
  format: yaml
  label: Acall Spot API
  slug: acall-spot-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acall/openapi/acall-spot-api-api-openapi.yml
- filename: acall-spot-reservation-api-api-openapi.yml
  format: yaml
  label: Acall Spot Reservation API
  slug: acall-spot-reservation-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acall/openapi/acall-spot-reservation-api-api-openapi.yml
- filename: acall-user-api-api-openapi.yml
  format: yaml
  label: Acall User API
  slug: acall-user-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acall/openapi/acall-user-api-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - JP
    text: 本システムの提供区域は、本規約で特に定める場合又はお客様との間で特に合意をした場合を除き、日本国内に限定されるものとします。
  entity_types:
  - text: お客様 ：本システムの利用に関する契約を当社と締結し、本システムの提供を受ける企業
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: 当社は、利用希望者が、以下の各号のいずれかの事由に該当する場合は、見積書や承諾書を発行しないことがあります。
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Acall
provenance_date: '2026-11-09'
provider_name: Acall
provider_slug: acall
slug: acall-eligibility
source_date: '2026-11-09'
source_filename: acall-eligibility.yml
source_heading: Eligibility
source_page: https://www.workstyleos.com/terms_of_use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Acall\naid: acall\nurl: https://www.workstyleos.com/terms_of_use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - JP\n  excluded: []\n  text: 本システムの提供区域は、本規約で特に定める場合又はお客様との間で特に合意をした場合を除き、日本国内に限定されるものとします。\nentity_types:\n- type: business\n  text: お客様 ：本システムの利用に関する契約を当社と締結し、本システムの提供を受ける企業\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: 当社は、利用希望者が、以下の各号のいずれかの事由に該当する場合は、見積書や承諾書を発行しないことがあります。\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/acall/eligibility/acall-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
summary_line: 3 quoted statements, read from Acall's own page on 2026-11-09.
synthetic: false
tags:
- Workplace Management
- Visitor Management
- Meeting Room Booking
- Desk Booking
- Hybrid Work
- Access Control
- Facilities
- Smart Office
- Japan
- Software-as-a-Service
---
