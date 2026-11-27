---
api_specs:
- filename: eventsend-io-openapi-generated.yml
  format: yaml
  label: EventSend API
  slug: eventsend-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventsend-io/openapi/_ae-authored/eventsend-io-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 and able to form a binding contract.
    type: individual
  - text: If you are agreeing on behalf of a company, you confirm you are authorised to bind it, and "you" means that company.
    type: business
  minimum_age:
    text: You must be at least 16 and able to form a binding contract.
    value: '16'
  restricted_uses:
  - summary: Life-safety, medical or emergency use
    text: Do not use the service as the sole channel for anything where a missed or delayed message would cause harm — including life-safety, medical, or emergency use.
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
name: EventSend
provenance_date: '2026-11-09'
provider_name: EventSend
provider_slug: eventsend-io
slug: eventsend-io-eligibility
source_date: '2026-11-09'
source_filename: eventsend-io-eligibility.yml
source_heading: Eligibility
source_page: https://eventsend.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EventSend\naid: eventsend-io\nurl: https://eventsend.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 and able to form a binding contract.\n- type: business\n  text: If you are agreeing on behalf of a company, you confirm you are authorised to bind it, and \"you\" means that\n    company.\nrestricted_uses:\n- summary: Life-safety, medical or emergency use\n  text: Do not use the service as the sole channel for anything where a missed or delayed message would cause harm\n    — including life-safety, medical,\
  \ or emergency use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 and able to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/eventsend-io/eligibility/eventsend-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from EventSend's own page on 2026-11-09.
synthetic: false
tags:
- Event Tracking
- Analytics
- Webhook
- Integration
- Product Teams
---
