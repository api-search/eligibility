---
api_specs:
- filename: sematext-alert-notifications-api-openapi.yml
  format: yaml
  label: Sematext Alert Notifications API
  slug: sematext-alert-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sematext/openapi/sematext-alert-notifications-api-openapi.yml
- filename: sematext-alerts-api-openapi.yml
  format: yaml
  label: Sematext Alerts API
  slug: sematext-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sematext/openapi/sematext-alerts-api-openapi.yml
- filename: sematext-app-guests-api-openapi.yml
  format: yaml
  label: Sematext App guests API
  slug: sematext-app-guests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sematext/openapi/sematext-app-guests-api-openapi.yml
- filename: sematext-app-ips-api-openapi.yml
  format: yaml
  label: Sematext App IPs API
  slug: sematext-app-ips-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sematext/openapi/sematext-app-ips-api-openapi.yml
- filename: sematext-app-tokens-api-openapi.yml
  format: yaml
  label: Sematext App tokens API
  slug: sematext-app-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sematext/openapi/sematext-app-tokens-api-openapi.yml
- filename: sematext-apps-api-openapi.yml
  format: yaml
  label: Sematext Apps API
  slug: sematext-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sematext/openapi/sematext-apps-api-openapi.yml
- filename: sematext-billing-api-openapi.yml
  format: yaml
  label: Sematext Billing API
  slug: sematext-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sematext/openapi/sematext-billing-api-openapi.yml
- filename: sematext-experience-app-api-openapi.yml
  format: yaml
  label: Sematext Experience App API
  slug: sematext-experience-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sematext/openapi/sematext-experience-app-api-openapi.yml
- filename: sematext-logs-app-api-openapi.yml
  format: yaml
  label: Sematext Logs App API
  slug: sematext-logs-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sematext/openapi/sematext-logs-app-api-openapi.yml
- filename: sematext-logs-app-usage-api-openapi.yml
  format: yaml
  label: Sematext Logs App usage API
  slug: sematext-logs-app-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sematext/openapi/sematext-logs-app-usage-api-openapi.yml
- filename: sematext-monitoring-app-api-openapi.yml
  format: yaml
  label: Sematext Monitoring App API
  slug: sematext-monitoring-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sematext/openapi/sematext-monitoring-app-api-openapi.yml
- filename: sematext-notifications-api-openapi.yml
  format: yaml
  label: Sematext Notifications API
  slug: sematext-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sematext/openapi/sematext-notifications-api-openapi.yml
- filename: sematext-reset-password-api-openapi.yml
  format: yaml
  label: Sematext Reset Password API
  slug: sematext-reset-password-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sematext/openapi/sematext-reset-password-api-openapi.yml
- filename: sematext-subscriptions-api-openapi.yml
  format: yaml
  label: Sematext Subscriptions API
  slug: sematext-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sematext/openapi/sematext-subscriptions-api-openapi.yml
- filename: sematext-tags-api-openapi.yml
  format: yaml
  label: Sematext Tags API
  slug: sematext-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sematext/openapi/sematext-tags-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: ALL THE SERVICES ARE AVAILABLE ONLY FOR INDIVIDUALS AGED 13 YEARS OR OLDER.
    type: individual
  minimum_age:
    text: ALL THE SERVICES ARE AVAILABLE ONLY FOR INDIVIDUALS AGED 13 YEARS OR OLDER.
    value: '13'
  restricted_uses:
  - summary: Unlawful or harmful content and conduct
    text: Violate any applicable law or regulation;
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
name: Sematext
provenance_date: '2026-11-10'
provider_name: Sematext
provider_slug: sematext
slug: sematext-eligibility
source_date: '2026-11-10'
source_filename: sematext-eligibility.yml
source_heading: Eligibility
source_page: https://sematext.com/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sematext\naid: sematext\nurl: https://sematext.com/legal/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: ALL THE SERVICES ARE AVAILABLE ONLY FOR INDIVIDUALS AGED 13 YEARS OR OLDER.\nrestricted_uses:\n- summary: Unlawful or harmful content and conduct\n  text: Violate any applicable law or regulation;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: ALL THE SERVICES ARE AVAILABLE ONLY FOR INDIVIDUALS AGED 13 YEARS OR OLDER.\n"
source_yaml_url: https://artifacts.apis.io/sematext/eligibility/sematext-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Sematext's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Observability
- Monitoring
- Logging
- Log Management
- Elasticsearch
- Tracing
- Synthetic Monitoring
- OpenTelemetry
---
