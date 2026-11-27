---
api_specs:
- filename: chili-piper-availability-api-openapi.yml
  format: yaml
  label: Chili Piper Availability API
  slug: chili-piper-availability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chili-piper/openapi/chili-piper-availability-api-openapi.yml
- filename: chili-piper-chat-api-openapi.yml
  format: yaml
  label: Chili Piper Chat API
  slug: chili-piper-chat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chili-piper/openapi/chili-piper-chat-api-openapi.yml
- filename: chili-piper-concierge-api-openapi.yml
  format: yaml
  label: Chili Piper Concierge API
  slug: chili-piper-concierge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chili-piper/openapi/chili-piper-concierge-api-openapi.yml
- filename: chili-piper-distribution-api-openapi.yml
  format: yaml
  label: Chili Piper Distribution API
  slug: chili-piper-distribution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chili-piper/openapi/chili-piper-distribution-api-openapi.yml
- filename: chili-piper-distro-api-openapi.yml
  format: yaml
  label: Chili Piper Distro API
  slug: chili-piper-distro-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chili-piper/openapi/chili-piper-distro-api-openapi.yml
- filename: chili-piper-meeting-type-api-openapi.yml
  format: yaml
  label: Chili Piper Meeting Type API
  slug: chili-piper-meeting-type-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chili-piper/openapi/chili-piper-meeting-type-api-openapi.yml
- filename: chili-piper-meeting-type-reminder-api-openapi.yml
  format: yaml
  label: Chili Piper Meeting Type Reminder API
  slug: chili-piper-meeting-type-reminder-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chili-piper/openapi/chili-piper-meeting-type-reminder-api-openapi.yml
- filename: chili-piper-meetings-api-openapi.yml
  format: yaml
  label: Chili Piper Meetings API
  slug: chili-piper-meetings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chili-piper/openapi/chili-piper-meetings-api-openapi.yml
- filename: chili-piper-rule-api-openapi.yml
  format: yaml
  label: Chili Piper Rule API
  slug: chili-piper-rule-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chili-piper/openapi/chili-piper-rule-api-openapi.yml
- filename: chili-piper-team-api-openapi.yml
  format: yaml
  label: Chili Piper Team API
  slug: chili-piper-team-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chili-piper/openapi/chili-piper-team-api-openapi.yml
- filename: chili-piper-tenant-api-openapi.yml
  format: yaml
  label: Chili Piper Tenant API
  slug: chili-piper-tenant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chili-piper/openapi/chili-piper-tenant-api-openapi.yml
- filename: chili-piper-user-api-openapi.yml
  format: yaml
  label: Chili Piper User API
  slug: chili-piper-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chili-piper/openapi/chili-piper-user-api-openapi.yml
- filename: chili-piper-workspace-api-openapi.yml
  format: yaml
  label: Chili Piper Workspace API
  slug: chili-piper-workspace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chili-piper/openapi/chili-piper-workspace-api-openapi.yml
- filename: chili-piper-hand-off-api-openapi.yml
  format: yaml
  label: Chili Piper Hand off API
  slug: chili-piper-hand-off-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chili-piper/openapi/chili-piper-hand-off-api-openapi.yml
- filename: chili-piper-scheduling-links-api-openapi.yml
  format: yaml
  label: Chili Piper Scheduling Links API
  slug: chili-piper-scheduling-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chili-piper/openapi/chili-piper-scheduling-links-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: You shall not permit Users to access or use Services in a U.S.-embargoed country (currently Cuba, Iran, North Korea, Sudan or Syria) or in violation of any U.S. export law or regulation.
  entity_types:
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Competitors barred without consent
    text: You may not access the Services if You are Our direct competitor, except with Our prior written consent.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Chili Piper
provenance_date: '2026-11-09'
provider_name: Chili Piper
provider_slug: chili-piper
slug: chili-piper-eligibility
source_date: '2026-11-09'
source_filename: chili-piper-eligibility.yml
source_heading: Eligibility
source_page: https://www.chilipiper.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chili Piper\naid: chili-piper\nurl: https://www.chilipiper.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: You shall not permit Users to access or use Services in a U.S.-embargoed country (currently Cuba, Iran,\n    North Korea, Sudan or Syria) or in violation of any U.S. export law or regulation.\nentity_types:\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT\n    YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY\nrestricted_uses:\n\
  - summary: Competitors barred without consent\n  text: You may not access the Services if You are Our direct competitor, except with Our prior written consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chili-piper/eligibility/chili-piper-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Chili Piper's own page on 2026-11-09.
synthetic: false
tags:
- Scheduling
- Lead Routing
- Meetings
- Sales
- Marketing
- CRM
- Demand Conversion
- Appointment Booking
- Revenue Operations
- Calendar
- Agents
- MCP
---
