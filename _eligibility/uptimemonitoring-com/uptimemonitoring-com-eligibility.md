---
api_specs:
- filename: uptimemonitoring-com-account-api-openapi.yml
  format: yaml
  label: Monitive Account API
  slug: uptimemonitoring-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uptimemonitoring-com/openapi/uptimemonitoring-com-account-api-openapi.yml
- filename: uptimemonitoring-com-admin-api-openapi.yml
  format: yaml
  label: Monitive Admin API
  slug: uptimemonitoring-com-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uptimemonitoring-com/openapi/uptimemonitoring-com-admin-api-openapi.yml
- filename: uptimemonitoring-com-announcements-api-openapi.yml
  format: yaml
  label: Monitive Announcements API
  slug: uptimemonitoring-com-announcements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uptimemonitoring-com/openapi/uptimemonitoring-com-announcements-api-openapi.yml
- filename: uptimemonitoring-com-email-api-openapi.yml
  format: yaml
  label: Monitive Email API
  slug: uptimemonitoring-com-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uptimemonitoring-com/openapi/uptimemonitoring-com-email-api-openapi.yml
- filename: uptimemonitoring-com-events-api-openapi.yml
  format: yaml
  label: Monitive Events API
  slug: uptimemonitoring-com-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uptimemonitoring-com/openapi/uptimemonitoring-com-events-api-openapi.yml
- filename: uptimemonitoring-com-feed-api-openapi.yml
  format: yaml
  label: Monitive Feed API
  slug: uptimemonitoring-com-feed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uptimemonitoring-com/openapi/uptimemonitoring-com-feed-api-openapi.yml
- filename: uptimemonitoring-com-feed-xml-api-openapi.yml
  format: yaml
  label: Monitive Feed.xml API
  slug: uptimemonitoring-com-feed-xml-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uptimemonitoring-com/openapi/uptimemonitoring-com-feed-xml-api-openapi.yml
- filename: uptimemonitoring-com-incidents-api-openapi.yml
  format: yaml
  label: Monitive Incidents API
  slug: uptimemonitoring-com-incidents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uptimemonitoring-com/openapi/uptimemonitoring-com-incidents-api-openapi.yml
- filename: uptimemonitoring-com-keys-api-openapi.yml
  format: yaml
  label: Monitive Keys API
  slug: uptimemonitoring-com-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uptimemonitoring-com/openapi/uptimemonitoring-com-keys-api-openapi.yml
- filename: uptimemonitoring-com-monitors-api-openapi.yml
  format: yaml
  label: Monitive Monitors API
  slug: uptimemonitoring-com-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uptimemonitoring-com/openapi/uptimemonitoring-com-monitors-api-openapi.yml
- filename: uptimemonitoring-com-oauth-api-openapi.yml
  format: yaml
  label: Monitive OAuth API
  slug: uptimemonitoring-com-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uptimemonitoring-com/openapi/uptimemonitoring-com-oauth-api-openapi.yml
- filename: uptimemonitoring-com-public-api-openapi.yml
  format: yaml
  label: Monitive Public API
  slug: uptimemonitoring-com-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uptimemonitoring-com/openapi/uptimemonitoring-com-public-api-openapi.yml
- filename: uptimemonitoring-com-push-api-openapi.yml
  format: yaml
  label: Monitive Push API
  slug: uptimemonitoring-com-push-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uptimemonitoring-com/openapi/uptimemonitoring-com-push-api-openapi.yml
- filename: uptimemonitoring-com-recipients-api-openapi.yml
  format: yaml
  label: Monitive Recipients API
  slug: uptimemonitoring-com-recipients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uptimemonitoring-com/openapi/uptimemonitoring-com-recipients-api-openapi.yml
- filename: uptimemonitoring-com-webhook-deliveries-api-openapi.yml
  format: yaml
  label: Monitive Webhook Deliveries API
  slug: uptimemonitoring-com-webhook-deliveries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uptimemonitoring-com/openapi/uptimemonitoring-com-webhook-deliveries-api-openapi.yml
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
  - summary: Unauthorized monitoring
    text: You may only monitor URLs and endpoints that you own or have explicit authorization to monitor.
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
name: Monitive
provenance_date: '2026-11-10'
provider_name: Monitive
provider_slug: uptimemonitoring-com
slug: uptimemonitoring-com-eligibility
source_date: '2026-11-10'
source_filename: uptimemonitoring-com-eligibility.yml
source_heading: Eligibility
source_page: https://uptimemonitoring.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Monitive\naid: uptimemonitoring-com\nurl: https://uptimemonitoring.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unauthorized monitoring\n  text: You may only monitor URLs and endpoints that you own or have explicit authorization to monitor.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/uptimemonitoring-com/eligibility/uptimemonitoring-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Monitive's own page on 2026-11-10.
synthetic: false
tags:
- Uptime Monitoring
- API-First
- Developer Tools
- Observability
- Software-as-a-Service
---
