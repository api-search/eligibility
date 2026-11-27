---
api_specs:
- filename: anjal-app-addresses-api-openapi.yml
  format: yaml
  label: Anjal Addresses API
  slug: anjal-app-addresses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anjal-app/openapi/anjal-app-addresses-api-openapi.yml
- filename: anjal-app-cadences-api-openapi.yml
  format: yaml
  label: Anjal Cadences API
  slug: anjal-app-cadences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anjal-app/openapi/anjal-app-cadences-api-openapi.yml
- filename: anjal-app-domains-api-openapi.yml
  format: yaml
  label: Anjal Domains API
  slug: anjal-app-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anjal-app/openapi/anjal-app-domains-api-openapi.yml
- filename: anjal-app-drafts-api-openapi.yml
  format: yaml
  label: Anjal Drafts API
  slug: anjal-app-drafts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anjal-app/openapi/anjal-app-drafts-api-openapi.yml
- filename: anjal-app-inboxes-api-openapi.yml
  format: yaml
  label: Anjal Inboxes API
  slug: anjal-app-inboxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anjal-app/openapi/anjal-app-inboxes-api-openapi.yml
- filename: anjal-app-linkedin-outreach-api-openapi.yml
  format: yaml
  label: Anjal LinkedIn — Outreach API
  slug: anjal-app-linkedin-outreach-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anjal-app/openapi/anjal-app-linkedin-outreach-api-openapi.yml
- filename: anjal-app-linkedin-posts-api-openapi.yml
  format: yaml
  label: Anjal LinkedIn — Posts API
  slug: anjal-app-linkedin-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anjal-app/openapi/anjal-app-linkedin-posts-api-openapi.yml
- filename: anjal-app-linkedin-searches-api-openapi.yml
  format: yaml
  label: Anjal LinkedIn — Searches API
  slug: anjal-app-linkedin-searches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anjal-app/openapi/anjal-app-linkedin-searches-api-openapi.yml
- filename: anjal-app-linkedin-sessions-api-openapi.yml
  format: yaml
  label: Anjal LinkedIn — Sessions API
  slug: anjal-app-linkedin-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anjal-app/openapi/anjal-app-linkedin-sessions-api-openapi.yml
- filename: anjal-app-linkedin-signals-api-openapi.yml
  format: yaml
  label: Anjal LinkedIn — Signals API
  slug: anjal-app-linkedin-signals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anjal-app/openapi/anjal-app-linkedin-signals-api-openapi.yml
- filename: anjal-app-lists-api-openapi.yml
  format: yaml
  label: Anjal Lists API
  slug: anjal-app-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anjal-app/openapi/anjal-app-lists-api-openapi.yml
- filename: anjal-app-messages-api-openapi.yml
  format: yaml
  label: Anjal Messages API
  slug: anjal-app-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anjal-app/openapi/anjal-app-messages-api-openapi.yml
- filename: anjal-app-metrics-api-openapi.yml
  format: yaml
  label: Anjal Metrics API
  slug: anjal-app-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anjal-app/openapi/anjal-app-metrics-api-openapi.yml
- filename: anjal-app-tenants-api-openapi.yml
  format: yaml
  label: Anjal Tenants API
  slug: anjal-app-tenants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anjal-app/openapi/anjal-app-tenants-api-openapi.yml
- filename: anjal-app-webhooks-api-openapi.yml
  format: yaml
  label: Anjal Webhooks API
  slug: anjal-app-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anjal-app/openapi/anjal-app-webhooks-api-openapi.yml
- filename: anjal-app-websocket-api-openapi.yml
  format: yaml
  label: Anjal WebSocket API
  slug: anjal-app-websocket-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anjal-app/openapi/anjal-app-websocket-api-openapi.yml
- filename: anjal-app-workspaces-api-openapi.yml
  format: yaml
  label: Anjal Workspaces API
  slug: anjal-app-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anjal-app/openapi/anjal-app-workspaces-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Prohibited content and senders
    text: Phishing, malware, and deception. Emails containing phishing links, malware payloads, fraudulent payment requests, or content designed to deceive recipients.
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
name: Anjal
provenance_date: '2026-11-09'
provider_name: Anjal
provider_slug: anjal-app
slug: anjal-app-eligibility
source_date: '2026-11-09'
source_filename: anjal-app-eligibility.yml
source_heading: Eligibility
source_page: https://anjal.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Anjal\naid: anjal-app\nurl: https://anjal.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited content and senders\n  text: Phishing, malware, and deception. Emails containing phishing links, malware payloads, fraudulent payment\n    requests, or content designed to deceive recipients.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/anjal-app/eligibility/anjal-app-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Anjal's own page on 2026-11-09.
synthetic: false
tags:
- Email
- Artificial Intelligence
- Agents
- Software-as-a-Service
- Email API
---
