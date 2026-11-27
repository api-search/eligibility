---
api_specs:
- filename: ando-calls-api-openapi.yml
  format: yaml
  label: Ando Calls API
  slug: ando-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ando/openapi/ando-calls-api-openapi.yml
- filename: ando-members-api-openapi.yml
  format: yaml
  label: Ando Members API
  slug: ando-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ando/openapi/ando-members-api-openapi.yml
- filename: ando-messages-api-openapi.yml
  format: yaml
  label: Ando Messages API
  slug: ando-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ando/openapi/ando-messages-api-openapi.yml
- filename: ando-realtime-api-openapi.yml
  format: yaml
  label: Ando Realtime API
  slug: ando-realtime-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ando/openapi/ando-realtime-api-openapi.yml
- filename: ando-search-api-openapi.yml
  format: yaml
  label: Ando Search API
  slug: ando-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ando/openapi/ando-search-api-openapi.yml
- filename: ando-webhooks-api-openapi.yml
  format: yaml
  label: Ando Webhooks API
  slug: ando-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ando/openapi/ando-webhooks-api-openapi.yml
- filename: ando-agents-api-openapi.yml
  format: yaml
  label: Ando Agents API
  slug: ando-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ando/openapi/ando-agents-api-openapi.yml
- filename: ando-api-keys-api-openapi.yml
  format: yaml
  label: Ando API Keys API
  slug: ando-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ando/openapi/ando-api-keys-api-openapi.yml
- filename: ando-conversations-api-openapi.yml
  format: yaml
  label: Ando Conversations API
  slug: ando-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ando/openapi/ando-conversations-api-openapi.yml
- filename: ando-files-api-openapi.yml
  format: yaml
  label: Ando Files API
  slug: ando-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ando/openapi/ando-files-api-openapi.yml
- filename: ando-imports-api-openapi.yml
  format: yaml
  label: Ando Imports API
  slug: ando-imports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ando/openapi/ando-imports-api-openapi.yml
- filename: ando-webhook-sources-api-openapi.yml
  format: yaml
  label: Ando Webhook sources API
  slug: ando-webhook-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ando/openapi/ando-webhook-sources-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using our services on behalf of an organization, you represent that you have the authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: you confirm that you are at least 13 years of age
    value: '13'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: You agree not to use our services for any unlawful purpose or in any way that could damage, disable, or impair the platform.
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
name: Ando
provenance_date: '2026-11-09'
provider_name: Ando
provider_slug: ando
slug: ando-eligibility
source_date: '2026-11-09'
source_filename: ando-eligibility.yml
source_heading: Eligibility
source_page: https://www.ando.so/security/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ando\naid: ando\nurl: https://www.ando.so/security/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using our services on behalf of an organization, you represent that you have the authority to\n    bind that organization to these Terms.\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: You agree not to use our services for any unlawful purpose or in any way that could damage, disable, or\n    impair the platform.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '13'\n  text: you confirm that you are at least 13 years of age\n"
source_yaml_url: https://artifacts.apis.io/ando/eligibility/ando-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Ando's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Business Applications
- Messaging
- Team Collaboration
- AI Agents
- Agents
- Developer Tools
- MCP
- Webhook
- Productivity
---
