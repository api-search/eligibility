---
api_specs:
- filename: hiver-conversations-api-openapi.yml
  format: yaml
  label: Hiver Conversations API
  slug: hiver-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hiver/openapi/hiver-conversations-api-openapi.yml
- filename: hiver-inbox-api-openapi.yml
  format: yaml
  label: Hiver Inbox API
  slug: hiver-inbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hiver/openapi/hiver-inbox-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the entity subscribing to the Services
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Internal use only
    text: use of the Services is limited to Customer’s internal use for their general business purposes to assist Clients.
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
name: Hiver
provenance_date: '2026-11-09'
provider_name: Hiver
provider_slug: hiver
slug: hiver-eligibility
source_date: '2026-11-09'
source_filename: hiver-eligibility.yml
source_heading: Eligibility
source_page: https://hiverhq.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hiver\naid: hiver\nurl: https://hiverhq.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the entity subscribing to the Services\nrestricted_uses:\n- summary: Internal use only\n  text: use of the Services is limited to Customer’s internal use for their general business purposes to assist\n    Clients.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hiver/eligibility/hiver-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Hiver's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Customer Service
- Help Desk
- Shared Inbox
- Email
- Ticketing
- Collaboration
- Gmail
- Google Workspace
- Omnichannel
- Live Chat
- Software-as-a-Service
- Artificial Intelligence
---
