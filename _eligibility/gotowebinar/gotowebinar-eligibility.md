---
api_specs:
- filename: gotowebinar-attendees-api-openapi.yml
  format: yaml
  label: GoToWebinar Attendees API
  slug: gotowebinar-attendees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gotowebinar/openapi/gotowebinar-attendees-api-openapi.yml
- filename: gotowebinar-co-organizers-api-openapi.yml
  format: yaml
  label: GoToWebinar Co-Organizers API
  slug: gotowebinar-co-organizers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gotowebinar/openapi/gotowebinar-co-organizers-api-openapi.yml
- filename: gotowebinar-panelists-api-openapi.yml
  format: yaml
  label: GoToWebinar Panelists API
  slug: gotowebinar-panelists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gotowebinar/openapi/gotowebinar-panelists-api-openapi.yml
- filename: gotowebinar-polls-api-openapi.yml
  format: yaml
  label: GoToWebinar Polls API
  slug: gotowebinar-polls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gotowebinar/openapi/gotowebinar-polls-api-openapi.yml
- filename: gotowebinar-questions-api-openapi.yml
  format: yaml
  label: GoToWebinar Questions API
  slug: gotowebinar-questions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gotowebinar/openapi/gotowebinar-questions-api-openapi.yml
- filename: gotowebinar-recordings-api-openapi.yml
  format: yaml
  label: GoToWebinar Recordings API
  slug: gotowebinar-recordings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gotowebinar/openapi/gotowebinar-recordings-api-openapi.yml
- filename: gotowebinar-registrants-api-openapi.yml
  format: yaml
  label: GoToWebinar Registrants API
  slug: gotowebinar-registrants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gotowebinar/openapi/gotowebinar-registrants-api-openapi.yml
- filename: gotowebinar-sessions-api-openapi.yml
  format: yaml
  label: GoToWebinar Sessions API
  slug: gotowebinar-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gotowebinar/openapi/gotowebinar-sessions-api-openapi.yml
- filename: gotowebinar-surveys-api-openapi.yml
  format: yaml
  label: GoToWebinar Surveys API
  slug: gotowebinar-surveys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gotowebinar/openapi/gotowebinar-surveys-api-openapi.yml
- filename: gotowebinar-user-subscriptions-api-openapi.yml
  format: yaml
  label: GoToWebinar User Subscriptions API
  slug: gotowebinar-user-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gotowebinar/openapi/gotowebinar-user-subscriptions-api-openapi.yml
- filename: gotowebinar-webhooks-api-openapi.yml
  format: yaml
  label: GoToWebinar Webhooks API
  slug: gotowebinar-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gotowebinar/openapi/gotowebinar-webhooks-api-openapi.yml
- filename: gotowebinar-webinars-api-openapi.yml
  format: yaml
  label: GoToWebinar Webinars API
  slug: gotowebinar-webinars-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gotowebinar/openapi/gotowebinar-webinars-api-openapi.yml
- filename: gotowebinar-recording-assets-api-openapi.yml
  format: yaml
  label: GoToWebinar Recording Assets API
  slug: gotowebinar-recording-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gotowebinar/openapi/gotowebinar-recording-assets-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'By completing any applicable registration process or by accessing or using any APIs offered by GoTo, you represent that you: (i) have the authority to bind the party using the APIs'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk activities
    text: 'the APIs and the Services are not designed or intended for access and/or use in or during high-risk activities including, but not limited to: medical procedures'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: GoTo may reject your Application registration in its sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: GoToWebinar
provenance_date: '2026-11-09'
provider_name: GoToWebinar
provider_slug: gotowebinar
slug: gotowebinar-eligibility
source_date: '2026-11-09'
source_filename: gotowebinar-eligibility.yml
source_heading: Eligibility
source_page: https://www.goto.com/company/legal/api-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GoToWebinar\naid: gotowebinar\nurl: https://www.goto.com/company/legal/api-terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'By completing any applicable registration process or by accessing or using any APIs offered by GoTo, you\n    represent that you: (i) have the authority to bind the party using the APIs'\nrestricted_uses:\n- summary: High-risk activities\n  text: 'the APIs and the Services are not designed or intended for access and/or use in or during high-risk activities\n    including, but not limited to: medical procedures'\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: GoTo may reject your Application registration in its sole discretion.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/gotowebinar/eligibility/gotowebinar-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from GoToWebinar's own page on 2026-11-09.
synthetic: false
tags:
- Attendees
- Collaboration
- Communications
- Event
- Meetings
- Registrants
- Sessions
- Surveys
- Video Conferencing
- Virtual Events
- Webhook
- Webinars
---
