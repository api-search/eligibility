---
api_specs:
- filename: billdog-io-openapi-generated.yml
  format: yaml
  label: BillDog API
  slug: billdog-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/billdog-io/openapi/_ae-authored/billdog-io-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: BillDog provides a subscription management platform that enables mobile app developers to implement, manage, and optimize in-app purchases and subscriptions.
    type: developer
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Fraud
    text: Use our services for fraudulent purposes
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
name: BillDog
provenance_date: '2026-11-09'
provider_name: BillDog
provider_slug: billdog-io
slug: billdog-io-eligibility
source_date: '2026-11-09'
source_filename: billdog-io-eligibility.yml
source_heading: Eligibility
source_page: https://billdog.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BillDog\naid: billdog-io\nurl: https://billdog.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: developer\n  text: BillDog provides a subscription management platform that enables mobile app developers to implement, manage,\n    and optimize in-app purchases and subscriptions.\nrestricted_uses:\n- summary: Fraud\n  text: Use our services for fraudulent purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/billdog-io/eligibility/billdog-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from BillDog's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Analytics
- Monetization
- Software-as-a-Service
- Platform
- Company
---
