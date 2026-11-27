---
api_specs:
- filename: novu-asyncapi.yml
  format: yaml
  label: Novu Inbox / In-App API
  slug: inbox-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/novu/asyncapi/novu-asyncapi.yml
- filename: novu-activity-api-openapi.yml
  format: yaml
  label: Novu Activity API
  slug: novu-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/novu/openapi/novu-activity-api-openapi.yml
- filename: novu-channel-connections-api-openapi.yml
  format: yaml
  label: Novu Channel Connections API
  slug: novu-channel-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/novu/openapi/novu-channel-connections-api-openapi.yml
- filename: novu-channel-endpoints-api-openapi.yml
  format: yaml
  label: Novu Channel Endpoints API
  slug: novu-channel-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/novu/openapi/novu-channel-endpoints-api-openapi.yml
- filename: novu-contexts-api-openapi.yml
  format: yaml
  label: Novu Contexts API
  slug: novu-contexts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/novu/openapi/novu-contexts-api-openapi.yml
- filename: novu-domains-api-openapi.yml
  format: yaml
  label: Novu Domains API
  slug: novu-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/novu/openapi/novu-domains-api-openapi.yml
- filename: novu-environment-variables-api-openapi.yml
  format: yaml
  label: Novu Environment Variables API
  slug: novu-environment-variables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/novu/openapi/novu-environment-variables-api-openapi.yml
- filename: novu-environments-api-openapi.yml
  format: yaml
  label: Novu Environments API
  slug: novu-environments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/novu/openapi/novu-environments-api-openapi.yml
- filename: novu-events-api-openapi.yml
  format: yaml
  label: Novu Events API
  slug: novu-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/novu/openapi/novu-events-api-openapi.yml
- filename: novu-integrations-api-openapi.yml
  format: yaml
  label: Novu Integrations API
  slug: novu-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/novu/openapi/novu-integrations-api-openapi.yml
- filename: novu-layouts-api-openapi.yml
  format: yaml
  label: Novu Layouts API
  slug: novu-layouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/novu/openapi/novu-layouts-api-openapi.yml
- filename: novu-messages-api-openapi.yml
  format: yaml
  label: Novu Messages API
  slug: novu-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/novu/openapi/novu-messages-api-openapi.yml
- filename: novu-notifications-api-openapi.yml
  format: yaml
  label: Novu Notifications API
  slug: novu-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/novu/openapi/novu-notifications-api-openapi.yml
- filename: novu-subscribers-api-openapi.yml
  format: yaml
  label: Novu Subscribers API
  slug: novu-subscribers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/novu/openapi/novu-subscribers-api-openapi.yml
- filename: novu-topics-api-openapi.yml
  format: yaml
  label: Novu Topics API
  slug: novu-topics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/novu/openapi/novu-topics-api-openapi.yml
- filename: novu-translations-api-openapi.yml
  format: yaml
  label: Novu Translations API
  slug: novu-translations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/novu/openapi/novu-translations-api-openapi.yml
- filename: novu-workflows-api-openapi.yml
  format: yaml
  label: Novu Workflows API
  slug: novu-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/novu/openapi/novu-workflows-api-openapi.yml
- filename: novu-webhooks-api-openapi.yml
  format: yaml
  label: Novu Webhooks API
  slug: novu-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/novu/openapi/novu-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: in the event that you create an Account on behalf of a company, you are entitled by it to create such Account
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sensitive data restriction
    text: you will not provide the Company with any sensitive or other categories of data that are subject to additional protections under law, such as data regarding children, finance, and health.
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
name: Novu
provenance_date: '2026-11-10'
provider_name: Novu
provider_slug: novu
slug: novu-eligibility
source_date: '2026-11-10'
source_filename: novu-eligibility.yml
source_heading: Eligibility
source_page: https://www.novu.co/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Novu\naid: novu\nurl: https://www.novu.co/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: in the event that you create an Account on behalf of a company, you are entitled by it to create such Account\nrestricted_uses:\n- summary: Sensitive data restriction\n  text: you will not provide the Company with any sensitive or other categories of data that are subject to additional\n    protections under law, such as data regarding children, finance, and health.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/novu/eligibility/novu-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Novu's own page on 2026-11-10.
synthetic: false
tags:
- Notification
- Messaging
- In-App
- Email
- SMS
- Push
- Chat
- Workflows
- Open Source
- Subscribers
- Topic
- Inbox
- Workflow Orchestration
- Multi-Channel
- Digest
- MCP
- Framework
- React
- Real-Time
---
