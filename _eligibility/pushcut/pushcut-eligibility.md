---
api_specs:
- filename: pushcut-automation-server-api-openapi.yml
  format: yaml
  label: Pushcut Automation Server API
  slug: pushcut-automation-server-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pushcut/openapi/pushcut-automation-server-api-openapi.yml
- filename: pushcut-notifications-api-openapi.yml
  format: yaml
  label: Pushcut Notifications API
  slug: pushcut-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pushcut/openapi/pushcut-notifications-api-openapi.yml
- filename: pushcut-subscriptions-api-openapi.yml
  format: yaml
  label: Pushcut Subscriptions API
  slug: pushcut-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pushcut/openapi/pushcut-subscriptions-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you represent that you are of legal age to form a binding contract and are not a person barred from receiving services under the laws of any applicable jurisdiction
    type: individual
  minimum_age:
    text: you represent that you are of legal age to form a binding contract
    value: null
  restricted_uses:
  - summary: Non-commercial personal use
    text: Permission is granted to temporarily download one copy of Pushcut per device for personal, non-commercial transitory viewing only.
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
name: Pushcut
provenance_date: '2026-11-10'
provider_name: Pushcut
provider_slug: pushcut
slug: pushcut-eligibility
source_date: '2026-11-10'
source_filename: pushcut-eligibility.yml
source_heading: Eligibility
source_page: https://www.pushcut.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pushcut\naid: pushcut\nurl: https://www.pushcut.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you represent that you are of legal age to form a binding contract and are not a person barred from receiving\n    services under the laws of any applicable jurisdiction\nrestricted_uses:\n- summary: Non-commercial personal use\n  text: Permission is granted to temporarily download one copy of Pushcut per device for personal, non-commercial\n    transitory viewing only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: you represent that you are of legal age to form a binding contract\n"
source_yaml_url: https://artifacts.apis.io/pushcut/eligibility/pushcut-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Pushcut's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Automation
- iOS
- Shortcuts
- Webhook
- Integration
---
