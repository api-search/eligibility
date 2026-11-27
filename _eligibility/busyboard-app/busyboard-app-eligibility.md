---
api_specs:
- filename: busyboard-app-api-openapi.yml
  format: yaml
  label: BusyBoard API API
  slug: busyboard-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/busyboard-app/openapi/_original/busyboard-app-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Each account is for individual use — do not share your credentials.
    type: individual
  - text: If you are using BusyBoard on behalf of an organization, you represent that you have authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You must be at least 16 years old to use BusyBoard.
    value: '16'
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
name: BusyBoard
provenance_date: '2026-11-09'
provider_name: BusyBoard
provider_slug: busyboard-app
slug: busyboard-app-eligibility
source_date: '2026-11-09'
source_filename: busyboard-app-eligibility.yml
source_heading: Eligibility
source_page: https://busyboard.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BusyBoard\naid: busyboard-app\nurl: https://busyboard.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Each account is for individual use — do not share your credentials.\n- type: business\n  text: If you are using BusyBoard on behalf of an organization, you represent that you have authority to bind that\n    organization to these Terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use BusyBoard.\n"
source_yaml_url: https://artifacts.apis.io/busyboard-app/eligibility/busyboard-app-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from BusyBoard's own page on 2026-11-09.
synthetic: false
tags:
- Scheduling
- Calendar
- Privacy
- Free
- Software-as-a-Service
---
