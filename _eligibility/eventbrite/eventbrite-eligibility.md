---
api_specs:
- filename: eventbrite-attendees-api-openapi.yml
  format: yaml
  label: Eventbrite Attendees API
  slug: eventbrite-attendees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventbrite/openapi/eventbrite-attendees-api-openapi.yml
- filename: eventbrite-categories-api-openapi.yml
  format: yaml
  label: Eventbrite Categories API
  slug: eventbrite-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventbrite/openapi/eventbrite-categories-api-openapi.yml
- filename: eventbrite-events-api-openapi.yml
  format: yaml
  label: Eventbrite Events API
  slug: eventbrite-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventbrite/openapi/eventbrite-events-api-openapi.yml
- filename: eventbrite-orders-api-openapi.yml
  format: yaml
  label: Eventbrite Orders API
  slug: eventbrite-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventbrite/openapi/eventbrite-orders-api-openapi.yml
- filename: eventbrite-organizations-api-openapi.yml
  format: yaml
  label: Eventbrite Organizations API
  slug: eventbrite-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventbrite/openapi/eventbrite-organizations-api-openapi.yml
- filename: eventbrite-ticket-classes-api-openapi.yml
  format: yaml
  label: Eventbrite Ticket Classes API
  slug: eventbrite-ticket-classes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventbrite/openapi/eventbrite-ticket-classes-api-openapi.yml
- filename: eventbrite-users-api-openapi.yml
  format: yaml
  label: Eventbrite Users API
  slug: eventbrite-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventbrite/openapi/eventbrite-users-api-openapi.yml
- filename: eventbrite-venues-api-openapi.yml
  format: yaml
  label: Eventbrite Venues API
  slug: eventbrite-venues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventbrite/openapi/eventbrite-venues-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: is located, organized, resident in, or the government of, any country or territory that is, at any time, the target of country- or territory-wide sanctions
  entity_types:
  - text: Using our Services on behalf of an entity will bind that entity to these Terms.
    type: business
  minimum_age:
    text: You must be the legal age of majority where you reside to use the Services.
    value: legal age of majority
  restricted_uses:
  - summary: No dealings with sanctioned areas or parties
    text: you will not use the Services in connection with any direct or indirect activities or dealings with or involving any Restricted Area or Restricted Party
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Eventbrite
provenance_date: '2026-11-09'
provider_name: Eventbrite
provider_slug: eventbrite
slug: eventbrite-eligibility
source_date: '2026-11-09'
source_filename: eventbrite-eligibility.yml
source_heading: Eligibility
source_page: https://www.eventbrite.com/help/en-us/articles/251210/eventbrite-terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Eventbrite\naid: eventbrite\nurl: https://www.eventbrite.com/help/en-us/articles/251210/eventbrite-terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: is located, organized, resident in, or the government of, any country or territory that is, at any time,\n    the target of country- or territory-wide sanctions\nentity_types:\n- type: business\n  text: Using our Services on behalf of an entity will bind that entity to these Terms.\nrestricted_uses:\n- summary: No dealings with sanctioned areas or parties\n  text: you will\
  \ not use the Services in connection with any direct or indirect activities or dealings with or involving\n    any Restricted Area or Restricted Party\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age of majority\n  text: You must be the legal age of majority where you reside to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/eventbrite/eligibility/eventbrite-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Eventbrite's own page on 2026-11-09.
synthetic: false
tags:
- Event
- Event Technology
- Ticketing
- Marketplace
---
