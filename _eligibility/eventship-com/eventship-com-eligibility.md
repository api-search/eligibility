---
api_specs:
- filename: eventship-com-attendees-api-openapi.yml
  format: yaml
  label: Eventship Attendees API
  slug: eventship-com-attendees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventship-com/openapi/eventship-com-attendees-api-openapi.yml
- filename: eventship-com-broadcast-api-openapi.yml
  format: yaml
  label: Eventship Broadcast API
  slug: eventship-com-broadcast-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventship-com/openapi/eventship-com-broadcast-api-openapi.yml
- filename: eventship-com-events-api-openapi.yml
  format: yaml
  label: Eventship Events API
  slug: eventship-com-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventship-com/openapi/eventship-com-events-api-openapi.yml
- filename: eventship-com-hubs-api-openapi.yml
  format: yaml
  label: Eventship Hubs API
  slug: eventship-com-hubs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventship-com/openapi/eventship-com-hubs-api-openapi.yml
- filename: eventship-com-questions-api-openapi.yml
  format: yaml
  label: Eventship Questions API
  slug: eventship-com-questions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventship-com/openapi/eventship-com-questions-api-openapi.yml
- filename: eventship-com-registration-api-openapi.yml
  format: yaml
  label: Eventship Registration API
  slug: eventship-com-registration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventship-com/openapi/eventship-com-registration-api-openapi.yml
- filename: eventship-com-speakers-api-openapi.yml
  format: yaml
  label: Eventship Speakers API
  slug: eventship-com-speakers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventship-com/openapi/eventship-com-speakers-api-openapi.yml
- filename: eventship-com-ticket-types-api-openapi.yml
  format: yaml
  label: Eventship Ticket Types API
  slug: eventship-com-ticket-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventship-com/openapi/eventship-com-ticket-types-api-openapi.yml
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
  restricted_uses:
  - summary: Prohibited API data uses
    text: Selling, renting, or otherwise distributing attendee data to third parties
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
name: Eventship
provenance_date: '2026-11-09'
provider_name: Eventship
provider_slug: eventship-com
slug: eventship-com-eligibility
source_date: '2026-11-09'
source_filename: eventship-com-eligibility.yml
source_heading: Eligibility
source_page: https://eventship.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Eventship\naid: eventship-com\nurl: https://eventship.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited API data uses\n  text: Selling, renting, or otherwise distributing attendee data to third parties\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/eventship-com/eligibility/eventship-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Eventship's own page on 2026-11-09.
synthetic: false
tags:
- Event
- Attendees
- Ticketing
- Event Management
---
