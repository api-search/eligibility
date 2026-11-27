---
api_specs:
- filename: addevent-calendar-subscribers-api-openapi.yml
  format: yaml
  label: AddEvent Calendar subscribers API
  slug: addevent-calendar-subscribers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/addevent/openapi/addevent-calendar-subscribers-api-openapi.yml
- filename: addevent-calendars-api-openapi.yml
  format: yaml
  label: AddEvent Calendars API
  slug: addevent-calendars-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/addevent/openapi/addevent-calendars-api-openapi.yml
- filename: addevent-events-api-openapi.yml
  format: yaml
  label: AddEvent Events API
  slug: addevent-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/addevent/openapi/addevent-events-api-openapi.yml
- filename: addevent-rsvp-attendees-api-openapi.yml
  format: yaml
  label: AddEvent RSVP attendees API
  slug: addevent-rsvp-attendees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/addevent/openapi/addevent-rsvp-attendees-api-openapi.yml
- filename: addevent-templates-api-openapi.yml
  format: yaml
  label: AddEvent Templates API
  slug: addevent-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/addevent/openapi/addevent-templates-api-openapi.yml
- filename: addevent-timezones-api-openapi.yml
  format: yaml
  label: AddEvent Timezones API
  slug: addevent-timezones-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/addevent/openapi/addevent-timezones-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are an organization, the individual who agrees to this Agreement on your behalf must have the authority to bind you to this Agreement.
    type: business
  minimum_age:
    text: If you collect any personal information pertaining to a minor and store such information within your AddEvent account, you represent and warrant that you have obtained valid consent
    value: null
  restricted_uses:
  - summary: Illegal or discriminatory activities
    text: You may not use the Service for any unlawful or discriminatory activities
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
name: AddEvent
provenance_date: '2026-11-09'
provider_name: AddEvent
provider_slug: addevent
slug: addevent-eligibility
source_date: '2026-11-09'
source_filename: addevent-eligibility.yml
source_heading: Eligibility
source_page: https://www.addevent.com/c/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AddEvent\naid: addevent\nurl: https://www.addevent.com/c/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are an organization, the individual who agrees to this Agreement on your behalf must have the authority\n    to bind you to this Agreement.\nrestricted_uses:\n- summary: Illegal or discriminatory activities\n  text: You may not use the Service for any unlawful or discriminatory activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: If you\
  \ collect any personal information pertaining to a minor and store such information within your AddEvent\n    account, you represent and warrant that you have obtained valid consent\n"
source_yaml_url: https://artifacts.apis.io/addevent/eligibility/addevent-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AddEvent's own page on 2026-11-09.
synthetic: false
tags:
- Calendar
- Integration
- Marketing
- Software-as-a-Service
- Event
---
