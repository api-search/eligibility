---
api_specs:
- filename: cherami-to-access-api-openapi.yml
  format: yaml
  label: Cherami Access API
  slug: cherami-to-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cherami-to/openapi/cherami-to-access-api-openapi.yml
- filename: cherami-to-drafts-api-openapi.yml
  format: yaml
  label: Cherami Drafts API
  slug: cherami-to-drafts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cherami-to/openapi/cherami-to-drafts-api-openapi.yml
- filename: cherami-to-feedback-api-openapi.yml
  format: yaml
  label: Cherami Feedback API
  slug: cherami-to-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cherami-to/openapi/cherami-to-feedback-api-openapi.yml
- filename: cherami-to-inboxes-api-openapi.yml
  format: yaml
  label: Cherami Inboxes API
  slug: cherami-to-inboxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cherami-to/openapi/cherami-to-inboxes-api-openapi.yml
- filename: cherami-to-labels-api-openapi.yml
  format: yaml
  label: Cherami Labels API
  slug: cherami-to-labels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cherami-to/openapi/cherami-to-labels-api-openapi.yml
- filename: cherami-to-messages-api-openapi.yml
  format: yaml
  label: Cherami Messages API
  slug: cherami-to-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cherami-to/openapi/cherami-to-messages-api-openapi.yml
- filename: cherami-to-sending-api-openapi.yml
  format: yaml
  label: Cherami Sending API
  slug: cherami-to-sending-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cherami-to/openapi/cherami-to-sending-api-openapi.yml
- filename: cherami-to-threads-api-openapi.yml
  format: yaml
  label: Cherami Threads API
  slug: cherami-to-threads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cherami-to/openapi/cherami-to-threads-api-openapi.yml
- filename: cherami-to-trash-api-openapi.yml
  format: yaml
  label: Cherami Trash API
  slug: cherami-to-trash-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cherami-to/openapi/cherami-to-trash-api-openapi.yml
- filename: cherami-to-webhooks-api-openapi.yml
  format: yaml
  label: Cherami Webhooks API
  slug: cherami-to-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cherami-to/openapi/cherami-to-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You need the legal capacity to accept them, and the authority to act for any person or organization you represent.
    type: individual
  - text: Each account has one human owner, the person who accepts these terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Bulk or unsolicited mail
    text: Newsletters, mailing lists and other bulk or marketing mail aren’t permitted, even to subscribers, and neither is unsolicited outreach, however personalized.
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
name: Cherami
provenance_date: '2026-11-09'
provider_name: Cherami
provider_slug: cherami-to
slug: cherami-to-eligibility
source_date: '2026-11-09'
source_filename: cherami-to-eligibility.yml
source_heading: Eligibility
source_page: https://cherami.to/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cherami\naid: cherami-to\nurl: https://cherami.to/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You need the legal capacity to accept them, and the authority to act for any person or organization you\n    represent.\n- type: business\n  text: Each account has one human owner, the person who accepts these terms.\nrestricted_uses:\n- summary: Bulk or unsolicited mail\n  text: Newsletters, mailing lists and other bulk or marketing mail aren’t permitted, even to subscribers, and neither\n    is unsolicited outreach, however personalized.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cherami-to/eligibility/cherami-to-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Cherami's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Email
- AI Agents
- MCP
- Webhook
- Messaging
- Email API
---
