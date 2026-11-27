---
api_specs:
- filename: zenzap-agentic-api-openapi.yml
  format: yaml
  label: ZenZap Agentic API
  slug: zenzap-agentic-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenzap/openapi/zenzap-agentic-api-openapi.yml
- filename: zenzap-long-polling-api-openapi.yml
  format: yaml
  label: ZenZap Long Polling API
  slug: zenzap-long-polling-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenzap/openapi/zenzap-long-polling-api-openapi.yml
- filename: zenzap-members-api-openapi.yml
  format: yaml
  label: ZenZap Members API
  slug: zenzap-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenzap/openapi/zenzap-members-api-openapi.yml
- filename: zenzap-messages-api-openapi.yml
  format: yaml
  label: ZenZap Messages API
  slug: zenzap-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenzap/openapi/zenzap-messages-api-openapi.yml
- filename: zenzap-polls-api-openapi.yml
  format: yaml
  label: ZenZap Polls API
  slug: zenzap-polls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenzap/openapi/zenzap-polls-api-openapi.yml
- filename: zenzap-tasks-api-openapi.yml
  format: yaml
  label: ZenZap Tasks API
  slug: zenzap-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenzap/openapi/zenzap-tasks-api-openapi.yml
- filename: zenzap-topics-group-chats-channels-conversations-api-openapi.yml
  format: yaml
  label: ZenZap Topics (group chats/channels/conversations) API
  slug: zenzap-topics-group-chats-channels-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenzap/openapi/zenzap-topics-group-chats-channels-conversations-api-openapi.yml
- filename: zenzap-oauth-api-openapi.yml
  format: yaml
  label: ZenZap O Auth API
  slug: zenzap-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenzap/openapi/zenzap-oauth-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is only intended for individuals aged 18 years or older.
    type: individual
  minimum_age:
    text: The Site is only intended for individuals aged 18 years or older.
    value: '18'
  restricted_uses:
  - summary: Unauthorized commercial communications
    text: use the communications systems provided by the Site to send unauthorized commercial communications
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
name: ZenZap
provenance_date: '2026-11-10'
provider_name: ZenZap
provider_slug: zenzap
slug: zenzap-eligibility
source_date: '2026-11-10'
source_filename: zenzap-eligibility.yml
source_heading: Eligibility
source_page: https://www.zenzap.co/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ZenZap\naid: zenzap\nurl: https://www.zenzap.co/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is only intended for individuals aged 18 years or older.\nrestricted_uses:\n- summary: Unauthorized commercial communications\n  text: use the communications systems provided by the Site to send unauthorized commercial communications\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is only intended for individuals aged 18 years or older.\n"
source_yaml_url: https://artifacts.apis.io/zenzap/eligibility/zenzap-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from ZenZap's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Messaging
- Team Communication
- Collaboration
- Chat
- Bots
- Webhook
- Productivity
- Task
---
