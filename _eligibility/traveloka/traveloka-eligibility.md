---
api_specs:
- filename: traveloka-1-1-content-hotel-room-api-openapi.yml
  format: yaml
  label: Traveloka 1.1 Content - Hotel & Room API
  slug: traveloka-1-1-content-hotel-room-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/traveloka/openapi/traveloka-1-1-content-hotel-room-api-openapi.yml
- filename: traveloka-2-1-search-hotellist-api-openapi.yml
  format: yaml
  label: Traveloka 2.1 Search - HotelList API
  slug: traveloka-2-1-search-hotellist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/traveloka/openapi/traveloka-2-1-search-hotellist-api-openapi.yml
- filename: traveloka-2-2-search-roomlist-api-openapi.yml
  format: yaml
  label: Traveloka 2.2 Search - RoomList API
  slug: traveloka-2-2-search-roomlist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/traveloka/openapi/traveloka-2-2-search-roomlist-api-openapi.yml
- filename: traveloka-2-3-search-bulkroomlist-api-openapi.yml
  format: yaml
  label: Traveloka 2.3 Search - BulkRoomList API
  slug: traveloka-2-3-search-bulkroomlist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/traveloka/openapi/traveloka-2-3-search-bulkroomlist-api-openapi.yml
- filename: traveloka-3-1-booking-book-api-openapi.yml
  format: yaml
  label: Traveloka 3.1 Booking - Book API
  slug: traveloka-3-1-booking-book-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/traveloka/openapi/traveloka-3-1-booking-book-api-openapi.yml
- filename: traveloka-3-2-booking-issuecheck-api-openapi.yml
  format: yaml
  label: Traveloka 3.2 Booking - IssueCheck API
  slug: traveloka-3-2-booking-issuecheck-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/traveloka/openapi/traveloka-3-2-booking-issuecheck-api-openapi.yml
- filename: traveloka-3-3-booking-issue-api-openapi.yml
  format: yaml
  label: Traveloka 3.3 Booking - Issue API
  slug: traveloka-3-3-booking-issue-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/traveloka/openapi/traveloka-3-3-booking-issue-api-openapi.yml
- filename: traveloka-3-4-booking-bookingsummary-api-openapi.yml
  format: yaml
  label: Traveloka 3.4 Booking - BookingSummary API
  slug: traveloka-3-4-booking-bookingsummary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/traveloka/openapi/traveloka-3-4-booking-bookingsummary-api-openapi.yml
- filename: traveloka-3-5-booking-cancel-api-openapi.yml
  format: yaml
  label: Traveloka 3.5 Booking - Cancel API
  slug: traveloka-3-5-booking-cancel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/traveloka/openapi/traveloka-3-5-booking-cancel-api-openapi.yml
- filename: traveloka-authorization-api-openapi.yml
  format: yaml
  label: Traveloka Authorization API
  slug: traveloka-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/traveloka/openapi/traveloka-authorization-api-openapi.yml
- filename: traveloka-booking-api-openapi.yml
  format: yaml
  label: Traveloka Booking API
  slug: traveloka-booking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/traveloka/openapi/traveloka-booking-api-openapi.yml
- filename: traveloka-content-api-openapi.yml
  format: yaml
  label: Traveloka Content API
  slug: traveloka-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/traveloka/openapi/traveloka-content-api-openapi.yml
- filename: traveloka-discovery-optional-api-openapi.yml
  format: yaml
  label: Traveloka Discovery (Optional) API
  slug: traveloka-discovery-optional-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/traveloka/openapi/traveloka-discovery-optional-api-openapi.yml
- filename: traveloka-rate-api-openapi.yml
  format: yaml
  label: Traveloka Rate API
  slug: traveloka-rate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/traveloka/openapi/traveloka-rate-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: A user having reached the legal age and being fully competent under the applicable laws shall be eligible to access any of our Services on the Site.
    type: individual
  minimum_age:
    text: A user having reached the legal age and being fully competent under the applicable laws shall be eligible to access any of our Services on the Site.
    value: legal age
  restricted_uses:
  - summary: Personal use only
    text: You agree not to use the Site or the Material for commercial purposes
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Please refer to our Privacy Notice on how we collect and process your personal data for your account registration purpose in accordance with our know-your-customer
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Traveloka
provenance_date: '2026-11-10'
provider_name: Traveloka
provider_slug: traveloka
slug: traveloka-eligibility
source_date: '2026-11-10'
source_filename: traveloka-eligibility.yml
source_heading: Eligibility
source_page: https://www.traveloka.com/en-id/termsandconditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Traveloka\naid: traveloka\nurl: https://www.traveloka.com/en-id/termsandconditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: A user having reached the legal age and being fully competent under the applicable laws shall be eligible\n    to access any of our Services on the Site.\nrestricted_uses:\n- summary: Personal use only\n  text: You agree not to use the Site or the Material for commercial purposes\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Please refer to our Privacy Notice\
  \ on how we collect and process your personal data for your account registration\n    purpose in accordance with our know-your-customer\nminimum_age:\n  value: legal age\n  text: A user having reached the legal age and being fully competent under the applicable laws shall be eligible\n    to access any of our Services on the Site.\n"
source_yaml_url: https://artifacts.apis.io/traveloka/eligibility/traveloka-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Traveloka's own page on 2026-11-10.
synthetic: false
tags:
- Travel
- Online Travel Agency
- Accommodation
- Hotel Booking
- Flights
- Activities
- Hospitality
- Distribution
- Channel Manager
- OpenTravel
- Southeast Asia
- Indonesia
- Hotels
---
