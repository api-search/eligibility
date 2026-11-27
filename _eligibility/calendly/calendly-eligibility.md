---
api_specs:
- filename: calendly-webhook-api-asyncapi.yml
  format: yaml
  label: Calendly Webhook API
  slug: webhook-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/calendly/asyncapi/calendly-webhook-api-asyncapi.yml
- filename: calendly-availability-api-openapi.yml
  format: yaml
  label: Calendly Availability API
  slug: calendly-availability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calendly/openapi/calendly-availability-api-openapi.yml
- filename: calendly-groups-api-openapi.yml
  format: yaml
  label: Calendly Groups API
  slug: calendly-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calendly/openapi/calendly-groups-api-openapi.yml
- filename: calendly-organizations-api-openapi.yml
  format: yaml
  label: Calendly Organizations API
  slug: calendly-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calendly/openapi/calendly-organizations-api-openapi.yml
- filename: calendly-shares-api-openapi.yml
  format: yaml
  label: Calendly Shares API
  slug: calendly-shares-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calendly/openapi/calendly-shares-api-openapi.yml
- filename: calendly-users-api-openapi.yml
  format: yaml
  label: Calendly Users API
  slug: calendly-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calendly/openapi/calendly-users-api-openapi.yml
- filename: calendly-activitylog-api-openapi.yml
  format: yaml
  label: Calendly Activity Log API
  slug: calendly-activitylog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calendly/openapi/calendly-activitylog-api-openapi.yml
- filename: calendly-contacts-api-openapi.yml
  format: yaml
  label: Calendly Contacts API
  slug: calendly-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calendly/openapi/calendly-contacts-api-openapi.yml
- filename: calendly-datacompliance-api-openapi.yml
  format: yaml
  label: Calendly Data Compliance API
  slug: calendly-datacompliance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calendly/openapi/calendly-datacompliance-api-openapi.yml
- filename: calendly-eventtypes-api-openapi.yml
  format: yaml
  label: Calendly Event Types API
  slug: calendly-eventtypes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calendly/openapi/calendly-eventtypes-api-openapi.yml
- filename: calendly-locations-api-openapi.yml
  format: yaml
  label: Calendly Locations API
  slug: calendly-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calendly/openapi/calendly-locations-api-openapi.yml
- filename: calendly-notetaker-api-openapi.yml
  format: yaml
  label: Calendly Notetaker API
  slug: calendly-notetaker-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calendly/openapi/calendly-notetaker-api-openapi.yml
- filename: calendly-outgoingcommunications-api-openapi.yml
  format: yaml
  label: Calendly Outgoing Communications API
  slug: calendly-outgoingcommunications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calendly/openapi/calendly-outgoingcommunications-api-openapi.yml
- filename: calendly-routingforms-api-openapi.yml
  format: yaml
  label: Calendly Routing Forms API
  slug: calendly-routingforms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calendly/openapi/calendly-routingforms-api-openapi.yml
- filename: calendly-scheduledevents-api-openapi.yml
  format: yaml
  label: Calendly Scheduled Events API
  slug: calendly-scheduledevents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calendly/openapi/calendly-scheduledevents-api-openapi.yml
- filename: calendly-webhooks-api-openapi.yml
  format: yaml
  label: Calendly Webhooks API
  slug: calendly-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calendly/openapi/calendly-webhooks-api-openapi.yml
- filename: calendly-scheduling-links-api-openapi.yml
  format: yaml
  label: Calendly Scheduling Links API
  slug: calendly-scheduling-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calendly/openapi/calendly-scheduling-links-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Calendly controls and operates the Services from our headquarters in the United States of America and the entirety of the Services may not be appropriate or available for use in other locations.
  entity_types:
  - text: If you are an individual Customer and registered using your personal email, you and you alone are entitled to the rights and responsible for the obligations under these Customer Terms.
    type: individual
  - text: If you are an Entity purchasing licenses for your Authorized Users, you may provision or deprovision access to the Services
    type: business
  minimum_age:
    text: The Services are not intended for and may not be used by individuals under 18 years of age
    value: '18'
  restricted_uses:
  - summary: Internal use only, no resale
    text: Use of the Services shall be limited to your internal business and not for resale or transfer.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Once you submit the required registration information, we will determine whether to approve your proposed account, at our sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Calendly
provenance_date: '2026-11-09'
provider_name: Calendly
provider_slug: calendly
slug: calendly-eligibility
source_date: '2026-11-09'
source_filename: calendly-eligibility.yml
source_heading: Eligibility
source_page: https://calendly.com/legal/customer-terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Calendly\naid: calendly\nurl: https://calendly.com/legal/customer-terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Calendly controls and operates the Services from our headquarters in the United States of America and the\n    entirety of the Services may not be appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: If you are an individual Customer and registered using your personal email, you and you alone are entitled\n    to the rights and responsible for the obligations under these Customer Terms.\n\
  - type: business\n  text: If you are an Entity purchasing licenses for your Authorized Users, you may provision or deprovision access\n    to the Services\nrestricted_uses:\n- summary: Internal use only, no resale\n  text: Use of the Services shall be limited to your internal business and not for resale or transfer.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Once you submit the required registration information, we will determine whether to approve your proposed\n    account, at our sole discretion.\nminimum_age:\n  value: '18'\n  text: The Services are not intended for and may not be used by individuals under 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/calendly/eligibility/calendly-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Calendly's own page on 2026-11-09.
synthetic: false
tags:
- Appointments
- Automation
- Booking
- Calendar
- Meetings
- Scheduling
---
