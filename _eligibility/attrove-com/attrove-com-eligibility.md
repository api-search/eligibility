---
api_specs:
- filename: attrove-com-a2a-api-openapi.yml
  format: yaml
  label: Attrove A2A API
  slug: attrove-com-a2a-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attrove-com/openapi/attrove-com-a2a-api-openapi.yml
- filename: attrove-com-calendars-api-openapi.yml
  format: yaml
  label: Attrove Calendars API
  slug: attrove-com-calendars-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attrove-com/openapi/attrove-com-calendars-api-openapi.yml
- filename: attrove-com-conversations-api-openapi.yml
  format: yaml
  label: Attrove Conversations API
  slug: attrove-com-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attrove-com/openapi/attrove-com-conversations-api-openapi.yml
- filename: attrove-com-entities-api-openapi.yml
  format: yaml
  label: Attrove Entities API
  slug: attrove-com-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attrove-com/openapi/attrove-com-entities-api-openapi.yml
- filename: attrove-com-events-api-openapi.yml
  format: yaml
  label: Attrove Events API
  slug: attrove-com-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attrove-com/openapi/attrove-com-events-api-openapi.yml
- filename: attrove-com-integrations-api-openapi.yml
  format: yaml
  label: Attrove Integrations API
  slug: attrove-com-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attrove-com/openapi/attrove-com-integrations-api-openapi.yml
- filename: attrove-com-meetings-api-openapi.yml
  format: yaml
  label: Attrove Meetings API
  slug: attrove-com-meetings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attrove-com/openapi/attrove-com-meetings-api-openapi.yml
- filename: attrove-com-messages-api-openapi.yml
  format: yaml
  label: Attrove Messages API
  slug: attrove-com-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attrove-com/openapi/attrove-com-messages-api-openapi.yml
- filename: attrove-com-notes-api-openapi.yml
  format: yaml
  label: Attrove Notes API
  slug: attrove-com-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attrove-com/openapi/attrove-com-notes-api-openapi.yml
- filename: attrove-com-push-api-openapi.yml
  format: yaml
  label: Attrove Push API
  slug: attrove-com-push-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attrove-com/openapi/attrove-com-push-api-openapi.yml
- filename: attrove-com-query-metered-api-openapi.yml
  format: yaml
  label: Attrove Query (Metered) API
  slug: attrove-com-query-metered-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attrove-com/openapi/attrove-com-query-metered-api-openapi.yml
- filename: attrove-com-search-metered-api-openapi.yml
  format: yaml
  label: Attrove Search (Metered) API
  slug: attrove-com-search-metered-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attrove-com/openapi/attrove-com-search-metered-api-openapi.yml
- filename: attrove-com-settings-api-openapi.yml
  format: yaml
  label: Attrove Settings API
  slug: attrove-com-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attrove-com/openapi/attrove-com-settings-api-openapi.yml
- filename: attrove-com-threads-api-openapi.yml
  format: yaml
  label: Attrove Threads API
  slug: attrove-com-threads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attrove-com/openapi/attrove-com-threads-api-openapi.yml
- filename: attrove-com-users-api-openapi.yml
  format: yaml
  label: Attrove Users API
  slug: attrove-com-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attrove-com/openapi/attrove-com-users-api-openapi.yml
- filename: attrove-com-webhooks-api-openapi.yml
  format: yaml
  label: Attrove Webhooks API
  slug: attrove-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attrove-com/openapi/attrove-com-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Be at least 18 years old or have parental consent
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Create an account with accurate information
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Attrove
provenance_date: '2026-11-09'
provider_name: Attrove
provider_slug: attrove-com
slug: attrove-com-eligibility
source_date: '2026-11-09'
source_filename: attrove-com-eligibility.yml
source_heading: Eligibility
source_page: https://attrove.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Attrove\naid: attrove-com\nurl: https://attrove.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Create an account with accurate information\nminimum_age:\n  value: '18'\n  text: Be at least 18 years old or have parental consent\n"
source_yaml_url: https://artifacts.apis.io/attrove-com/eligibility/attrove-com-eligibility.yml
stated_fields:
- verification
- minimum_age
summary_line: 2 quoted statements, read from Attrove's own page on 2026-11-09.
synthetic: false
tags:
- Commitments
- Workflows
- Automation
- Integration
- Monitoring
---
