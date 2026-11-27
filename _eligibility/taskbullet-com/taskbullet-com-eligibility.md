---
api_specs:
- filename: taskbullet-com-api-openapi.json
  format: json
  label: TaskBullet Agent API API
  slug: taskbullet-agent-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/taskbullet-com/openapi/_original/taskbullet-com-api-openapi.json
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: TaskBullet provides managed virtual assistant services to US entrepreneurs and small business owners.
  entity_types:
  - text: TaskBullet provides managed virtual assistant services to US entrepreneurs and small business owners.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful purposes
    text: TaskBullet reserves the right to terminate your account if you violate these Terms, use the service for unlawful purposes, or engage in abusive conduct toward our team.
  - summary: Non-resale of lists; FCRA uses
    text: You may not resell the file or use it for credit, employment, insurance, or other Fair Credit Reporting Act purposes.
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
name: taskbullet-com
provenance_date: '2026-11-10'
provider_name: taskbullet-com
provider_slug: taskbullet-com
slug: taskbullet-com-eligibility
source_date: '2026-11-10'
source_filename: taskbullet-com-eligibility.yml
source_heading: Eligibility
source_page: https://taskbullet.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: taskbullet-com\naid: taskbullet-com\nurl: https://taskbullet.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: TaskBullet provides managed virtual assistant services to US entrepreneurs and small business owners.\nentity_types:\n- type: business\n  text: TaskBullet provides managed virtual assistant services to US entrepreneurs and small business owners.\nrestricted_uses:\n- summary: Unlawful purposes\n  text: TaskBullet reserves the right to terminate your account if you violate these Terms, use the service for\n    unlawful purposes, or engage in abusive conduct\
  \ toward our team.\n- summary: Non-resale of lists; FCRA uses\n  text: You may not resell the file or use it for credit, employment, insurance, or other Fair Credit Reporting\n    Act purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/taskbullet-com/eligibility/taskbullet-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from taskbullet-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Virtual Assistant
- Software-as-a-Service
- US Business
- Productivity
---
