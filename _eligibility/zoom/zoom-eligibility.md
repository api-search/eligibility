---
api_specs:
- filename: zoom-meeting--openapi-original.yml
  format: yaml
  label: Zoom Meeting API
  slug: zoom-meeting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zoom/openapi/_original/zoom-meeting--openapi-original.yml
- filename: zoom-account-api-openapi.yml
  format: yaml
  label: Zoom Account API
  slug: zoom-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zoom/openapi/zoom-account-api-openapi.yml
- filename: zoom-chat-api-openapi.yml
  format: yaml
  label: Zoom Chat API
  slug: zoom-chat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zoom/openapi/zoom-chat-api-openapi.yml
- filename: zoom-cloud-recording-api-openapi.yml
  format: yaml
  label: Zoom Cloud Recording API
  slug: zoom-cloud-recording-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zoom/openapi/zoom-cloud-recording-api-openapi.yml
- filename: zoom-dashboard-api-openapi.yml
  format: yaml
  label: Zoom Dashboard API
  slug: zoom-dashboard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zoom/openapi/zoom-dashboard-api-openapi.yml
- filename: zoom-device-api-openapi.yml
  format: yaml
  label: Zoom Device API
  slug: zoom-device-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zoom/openapi/zoom-device-api-openapi.yml
- filename: zoom-group-api-openapi.yml
  format: yaml
  label: Zoom Group API
  slug: zoom-group-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zoom/openapi/zoom-group-api-openapi.yml
- filename: zoom-im-group-api-openapi.yml
  format: yaml
  label: Zoom IM Group API
  slug: zoom-im-group-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zoom/openapi/zoom-im-group-api-openapi.yml
- filename: zoom-meeting-live-stream-api-openapi.yml
  format: yaml
  label: Zoom Meeting Live Stream API
  slug: zoom-meeting-live-stream-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zoom/openapi/zoom-meeting-live-stream-api-openapi.yml
- filename: zoom-meeting-participants-api-openapi.yml
  format: yaml
  label: Zoom Meeting Participants API
  slug: zoom-meeting-participants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zoom/openapi/zoom-meeting-participants-api-openapi.yml
- filename: zoom-meeting-polls-api-openapi.yml
  format: yaml
  label: Zoom Meeting Polls API
  slug: zoom-meeting-polls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zoom/openapi/zoom-meeting-polls-api-openapi.yml
- filename: zoom-meeting-recordings-api-openapi.yml
  format: yaml
  label: Zoom Meeting Recordings API
  slug: zoom-meeting-recordings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zoom/openapi/zoom-meeting-recordings-api-openapi.yml
- filename: zoom-meeting-registrants-api-openapi.yml
  format: yaml
  label: Zoom Meeting Registrants API
  slug: zoom-meeting-registrants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zoom/openapi/zoom-meeting-registrants-api-openapi.yml
- filename: zoom-meetings-api-openapi.yml
  format: yaml
  label: Zoom Meetings API
  slug: zoom-meetings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zoom/openapi/zoom-meetings-api-openapi.yml
- filename: zoom-report-api-openapi.yml
  format: yaml
  label: Zoom Report API
  slug: zoom-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zoom/openapi/zoom-report-api-openapi.yml
- filename: zoom-user-api-openapi.yml
  format: yaml
  label: Zoom User API
  slug: zoom-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zoom/openapi/zoom-user-api-openapi.yml
- filename: zoom-webinar-api-openapi.yml
  format: yaml
  label: Zoom Webinar API
  slug: zoom-webinar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zoom/openapi/zoom-webinar-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Services may not be used by or in countries subject to U.S. trade sanctions, including Cuba, Iran, North Korea, Syria, and the Crimea, Donetsk and Luhansk regions of Ukraine.
  entity_types:
  - text: You may enter into this Agreement on behalf of yourself or on behalf of a legal entity.
    type: individual
  - text: If you enter into this Agreement on behalf of a legal entity, you represent that you are a duly authorized representative with the authority to bind that legal entity to this Agreement.
    type: business
  minimum_age:
    text: Zoom is not intended for use by individuals under the age of sixteen (16) years old, unless it is through a School Subscriber
    value: '16'
  restricted_uses:
  - summary: No high-risk use
    text: THE SERVICES AND SOFTWARE ARE NOT DESIGNED FOR USE IN HAZARDOUS OR HIGH-RISK ENVIRONMENTS REQUIRING FAIL-SAFE CONTROLS, INCLUDING OPERATION OF NUCLEAR FACILITIES, AIRCRAFT NAVIGATION OR COMMUNICATION SYSTEMS, AIR TRAFFIC CONTROL, LIFE SUPPORT, COMBAT OPERATIONS, OR WEAPONS SYSTEMS.
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
name: Zoom
provenance_date: '2026-11-10'
provider_name: Zoom
provider_slug: zoom
slug: zoom-eligibility
source_date: '2026-11-10'
source_filename: zoom-eligibility.yml
source_heading: Eligibility
source_page: https://www.zoom.com/en/trust/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zoom\naid: zoom\nurl: https://www.zoom.com/en/trust/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Services may not be used by or in countries subject to U.S. trade sanctions, including Cuba, Iran, North\n    Korea, Syria, and the Crimea, Donetsk and Luhansk regions of Ukraine.\nentity_types:\n- type: individual\n  text: You may enter into this Agreement on behalf of yourself or on behalf of a legal entity.\n- type: business\n  text: If you enter into this Agreement on behalf of a legal entity, you represent that you are a duly authorized\n    representative\
  \ with the authority to bind that legal entity to this Agreement.\nrestricted_uses:\n- summary: No high-risk use\n  text: THE SERVICES AND SOFTWARE ARE NOT DESIGNED FOR USE IN HAZARDOUS OR HIGH-RISK ENVIRONMENTS REQUIRING FAIL-SAFE\n    CONTROLS, INCLUDING OPERATION OF NUCLEAR FACILITIES, AIRCRAFT NAVIGATION OR COMMUNICATION SYSTEMS, AIR TRAFFIC\n    CONTROL, LIFE SUPPORT, COMBAT OPERATIONS, OR WEAPONS SYSTEMS.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: Zoom is not intended for use by individuals under the age of sixteen (16) years old, unless it is through\n    a School Subscriber\n"
source_yaml_url: https://artifacts.apis.io/zoom/eligibility/zoom-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Zoom's own page on 2026-11-10.
synthetic: false
tags:
- Video
- Zoom
- Chat
- Collaboration
- Communications
- Meetings
- Video Conferencing
- Webinars
---
