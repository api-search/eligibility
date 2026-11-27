---
api_specs:
- filename: dead-drop-documentation-api-openapi.yml
  format: yaml
  label: Dead Drop Documentation API
  slug: dead-drop-documentation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dead-drop/openapi/dead-drop-documentation-api-openapi.yml
- filename: dead-drop-drops-api-openapi.yml
  format: yaml
  label: Dead Drop Drops API
  slug: dead-drop-drops-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dead-drop/openapi/dead-drop-drops-api-openapi.yml
- filename: dead-drop-health-api-openapi.yml
  format: yaml
  label: Dead Drop Health API
  slug: dead-drop-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dead-drop/openapi/dead-drop-health-api-openapi.yml
- filename: dead-drop-history-api-openapi.yml
  format: yaml
  label: Dead Drop History API
  slug: dead-drop-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dead-drop/openapi/dead-drop-history-api-openapi.yml
claim_count: 1
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
  - summary: Illegal use and malware
    text: 'You agree not to use the Service for any illegal activities, including but not limited to: (a) sharing illegal content, (b) facilitating illegal activities, (c) violating any applicable laws or regulations, (d) distributing malware or harmful software, (e) harassment or abuse of others.'
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
name: Dead Drop
provenance_date: '2026-11-09'
provider_name: Dead Drop
provider_slug: dead-drop
slug: dead-drop-eligibility
source_date: '2026-11-09'
source_filename: dead-drop-eligibility.yml
source_heading: Eligibility
source_page: https://dead-drop.xyz/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dead Drop\naid: dead-drop\nurl: https://dead-drop.xyz/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal use and malware\n  text: 'You agree not to use the Service for any illegal activities, including but not limited to: (a) sharing\n    illegal content, (b) facilitating illegal activities, (c) violating any applicable laws or regulations, (d)\n    distributing malware or harmful software, (e) harassment or abuse of others.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dead-drop/eligibility/dead-drop-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Dead Drop's own page on 2026-11-09.
synthetic: false
tags:
- Messaging
- Privacy
- Anonymous
- Open Source
---
