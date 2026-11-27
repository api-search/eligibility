---
api_specs:
- filename: avoca-analytics-v1-api-openapi.yml
  format: yaml
  label: Avoca Analytics (v1) API
  slug: avoca-analytics-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avoca/openapi/avoca-analytics-v1-api-openapi.yml
- filename: avoca-calls-api-openapi.yml
  format: yaml
  label: Avoca Calls API
  slug: avoca-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avoca/openapi/avoca-calls-api-openapi.yml
- filename: avoca-coach-api-openapi.yml
  format: yaml
  label: Avoca Coach API
  slug: avoca-coach-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avoca/openapi/avoca-coach-api-openapi.yml
- filename: avoca-leads-api-openapi.yml
  format: yaml
  label: Avoca Leads API
  slug: avoca-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avoca/openapi/avoca-leads-api-openapi.yml
- filename: avoca-outbound-texting-api-openapi.yml
  format: yaml
  label: Avoca Outbound Texting API
  slug: avoca-outbound-texting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avoca/openapi/avoca-outbound-texting-api-openapi.yml
- filename: avoca-scheduler-analytics-v0-api-openapi.yml
  format: yaml
  label: Avoca Scheduler Analytics (v0) API
  slug: avoca-scheduler-analytics-v0-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avoca/openapi/avoca-scheduler-analytics-v0-api-openapi.yml
- filename: avoca-sessions-bookings-api-openapi.yml
  format: yaml
  label: Avoca Sessions & Bookings API
  slug: avoca-sessions-bookings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avoca/openapi/avoca-sessions-bookings-api-openapi.yml
- filename: avoca-teams-api-openapi.yml
  format: yaml
  label: Avoca Teams API
  slug: avoca-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avoca/openapi/avoca-teams-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site is intended for visitors located within the United States.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal purposes
    text: use the Site for any illegal purpose or in violation of any local, state, national, or international law
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
name: Avoca
provenance_date: '2026-11-09'
provider_name: Avoca
provider_slug: avoca
slug: avoca-eligibility
source_date: '2026-11-09'
source_filename: avoca-eligibility.yml
source_heading: Eligibility
source_page: https://www.avoca.ai/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Avoca\naid: avoca\nurl: https://www.avoca.ai/legal/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site is intended for visitors located within the United States.\nentity_types: []\nrestricted_uses:\n- summary: Illegal purposes\n  text: use the Site for any illegal purpose or in violation of any local, state, national, or international law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/avoca/eligibility/avoca-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Avoca's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Voice AI
- Conversational AI
- Customer Service
- Contact Center
- Home Services
- Field Service Management
- Scheduling
- Analytics
- Webhook
- Enterprise API
---
