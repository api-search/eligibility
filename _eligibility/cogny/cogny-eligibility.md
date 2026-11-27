---
api_specs:
- filename: cogny-reports-api-openapi.yml
  format: yaml
  label: Cogny Reports API
  slug: cogny-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cogny/openapi/cogny-reports-api-openapi.yml
- filename: cogny-tickets-api-openapi.yml
  format: yaml
  label: Cogny Tickets API
  slug: cogny-tickets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cogny/openapi/cogny-tickets-api-openapi.yml
- filename: cogny-warehouses-api-openapi.yml
  format: yaml
  label: Cogny Warehouses API
  slug: cogny-warehouses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cogny/openapi/cogny-warehouses-api-openapi.yml
- filename: cogny-webhooks-api-openapi.yml
  format: yaml
  label: Cogny Webhooks API
  slug: cogny-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cogny/openapi/cogny-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You are not located in a country subject to a Swedish Government embargo or designated as a “terrorist-supporting” country by the Swedish Government.
  entity_types:
  - text: Have the legal capacity to form a binding contract (natural persons).
    type: individual
  - text: Be an authorized representative of a legal entity (legal persons).
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Automated execution for business use only
    text: Features that let Cogny make changes without your approval of each change, including YOLO Mode, auto-merge, and other auto-approval settings, are optional, off by default, and for business use only.
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
name: Cogny
provenance_date: '2026-11-09'
provider_name: Cogny
provider_slug: cogny
slug: cogny-eligibility
source_date: '2026-11-09'
source_filename: cogny-eligibility.yml
source_heading: Eligibility
source_page: https://cogny.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cogny\naid: cogny\nurl: https://cogny.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You are not located in a country subject to a Swedish Government embargo or designated as a “terrorist-supporting”\n    country by the Swedish Government.\nentity_types:\n- type: individual\n  text: Have the legal capacity to form a binding contract (natural persons).\n- type: business\n  text: Be an authorized representative of a legal entity (legal persons).\nrestricted_uses:\n- summary: Automated execution for business use only\n  text: Features that let Cogny make changes without your\
  \ approval of each change, including YOLO Mode, auto-merge,\n    and other auto-approval settings, are optional, off by default, and for business use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cogny/eligibility/cogny-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Cogny's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Ai Enterprise Software
- Marketing
- Marketing Analytics
- Marketing Automation
- MCP
- Agents
- Data Warehouse
- Advertising
---
