---
api_specs:
- filename: levitate-companies-api-openapi.yml
  format: yaml
  label: Levitate Companies API
  slug: levitate-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/levitate/openapi/levitate-companies-api-openapi.yml
- filename: levitate-contacts-api-openapi.yml
  format: yaml
  label: Levitate Contacts API
  slug: levitate-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/levitate/openapi/levitate-contacts-api-openapi.yml
- filename: levitate-notes-api-openapi.yml
  format: yaml
  label: Levitate Notes API
  slug: levitate-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/levitate/openapi/levitate-notes-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: '"Territory" means the entire world, excluding countries that are the subject of embargoes or sanctions by the U.S.'
  minimum_age:
    text: In order to access and use the Services, you must be at least eighteen (18) years old.
    value: '18'
  restricted_uses:
  - summary: Prohibited Content categories
    text: Content which could cause the Company to violate any law or regulation
  - summary: Health information in Content
    text: information that can identify an individual in relation to any past, present or future physical or mental health or condition
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
name: Levitate
provenance_date: '2026-11-09'
provider_name: Levitate
provider_slug: levitate
slug: levitate-eligibility
source_date: '2026-11-09'
source_filename: levitate-eligibility.yml
source_heading: Eligibility
source_page: https://www.levitate.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Levitate\naid: levitate\nurl: https://www.levitate.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: '\"Territory\" means the entire world, excluding countries that are the subject of embargoes or sanctions\n    by the U.S.'\nentity_types: []\nrestricted_uses:\n- summary: Prohibited Content categories\n  text: Content which could cause the Company to violate any law or regulation\n- summary: Health information in Content\n  text: information that can identify an individual in relation to any past, present or future physical or mental\n    health or condition\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: In order to access and use the Services, you must be at least eighteen (18) years old.\n"
source_yaml_url: https://artifacts.apis.io/levitate/eligibility/levitate-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Levitate's own page on 2026-11-09.
synthetic: false
tags:
- relationship-marketing
- CRM
- Email Marketing
- Contacts
- Small Business
- Insurance
- Financial Services
- Non-Profit
- Marketing Automation
- MCP
- Agent-Native
- Software-as-a-Service
---
