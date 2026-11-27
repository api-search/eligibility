---
api_specs:
- filename: chatrail-dev-ai-api-openapi.yml
  format: yaml
  label: chatrail-dev AI API
  slug: chatrail-dev-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chatrail-dev/openapi/chatrail-dev-ai-api-openapi.yml
- filename: chatrail-dev-auth-api-openapi.yml
  format: yaml
  label: chatrail-dev Auth API
  slug: chatrail-dev-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chatrail-dev/openapi/chatrail-dev-auth-api-openapi.yml
- filename: chatrail-dev-billing-api-openapi.yml
  format: yaml
  label: chatrail-dev Billing API
  slug: chatrail-dev-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chatrail-dev/openapi/chatrail-dev-billing-api-openapi.yml
- filename: chatrail-dev-connections-api-openapi.yml
  format: yaml
  label: chatrail-dev Connections API
  slug: chatrail-dev-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chatrail-dev/openapi/chatrail-dev-connections-api-openapi.yml
- filename: chatrail-dev-groups-api-openapi.yml
  format: yaml
  label: chatrail-dev Groups API
  slug: chatrail-dev-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chatrail-dev/openapi/chatrail-dev-groups-api-openapi.yml
- filename: chatrail-dev-internal-api-openapi.yml
  format: yaml
  label: chatrail-dev Internal API
  slug: chatrail-dev-internal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chatrail-dev/openapi/chatrail-dev-internal-api-openapi.yml
- filename: chatrail-dev-mcp-api-openapi.yml
  format: yaml
  label: chatrail-dev MCP API
  slug: chatrail-dev-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chatrail-dev/openapi/chatrail-dev-mcp-api-openapi.yml
- filename: chatrail-dev-messages-api-openapi.yml
  format: yaml
  label: chatrail-dev Messages API
  slug: chatrail-dev-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chatrail-dev/openapi/chatrail-dev-messages-api-openapi.yml
- filename: chatrail-dev-operational-api-openapi.yml
  format: yaml
  label: chatrail-dev Operational API
  slug: chatrail-dev-operational-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chatrail-dev/openapi/chatrail-dev-operational-api-openapi.yml
- filename: chatrail-dev-opt-outs-api-openapi.yml
  format: yaml
  label: chatrail-dev Opt Outs API
  slug: chatrail-dev-opt-outs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chatrail-dev/openapi/chatrail-dev-opt-outs-api-openapi.yml
- filename: chatrail-dev-schedules-api-openapi.yml
  format: yaml
  label: chatrail-dev Schedules API
  slug: chatrail-dev-schedules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chatrail-dev/openapi/chatrail-dev-schedules-api-openapi.yml
- filename: chatrail-dev-team-api-openapi.yml
  format: yaml
  label: chatrail-dev Team API
  slug: chatrail-dev-team-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chatrail-dev/openapi/chatrail-dev-team-api-openapi.yml
- filename: chatrail-dev-webhooks-api-openapi.yml
  format: yaml
  label: chatrail-dev Webhooks API
  slug: chatrail-dev-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chatrail-dev/openapi/chatrail-dev-webhooks-api-openapi.yml
- filename: chatrail-dev-workspace-api-openapi.yml
  format: yaml
  label: chatrail-dev Workspace API
  slug: chatrail-dev-workspace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chatrail-dev/openapi/chatrail-dev-workspace-api-openapi.yml
claim_count: 2
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
  - summary: Unsolicited or unlawful messaging
    text: complying with WhatsApp’s terms and policies, and with the law that applies to you and your recipients — including rules on unsolicited messaging, which are strict in many countries.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you must give an email address you control — sign-in is a one-time code sent to it
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: chatrail-dev
provenance_date: '2026-11-09'
provider_name: chatrail-dev
provider_slug: chatrail-dev
slug: chatrail-dev-eligibility
source_date: '2026-11-09'
source_filename: chatrail-dev-eligibility.yml
source_heading: Eligibility
source_page: https://www.chatrail.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: chatrail-dev\naid: chatrail-dev\nurl: https://www.chatrail.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unsolicited or unlawful messaging\n  text: complying with WhatsApp’s terms and policies, and with the law that applies to you and your recipients —\n    including rules on unsolicited messaging, which are strict in many countries.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you must give an email address you control — sign-in is a one-time code sent to it\nminimum_age:\n  value: null\n\
  \  text: null\n"
source_yaml_url: https://artifacts.apis.io/chatrail-dev/eligibility/chatrail-dev-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from chatrail-dev's own page on 2026-11-09.
synthetic: false
tags:
- WhatsApp
- Messaging
- Artificial Intelligence
- Developers
---
