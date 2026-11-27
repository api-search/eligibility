---
api_specs:
- filename: trellistech-properties-api-openapi.yml
  format: yaml
  label: Trellis Properties API
  slug: trellistech-properties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trellistech/openapi/trellistech-properties-api-openapi.yml
- filename: trellistech-tasks-api-openapi.yml
  format: yaml
  label: Trellis Tasks API
  slug: trellistech-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trellistech/openapi/trellistech-tasks-api-openapi.yml
claim_count: 2
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
  - summary: Acceptable use restrictions
    text: Engaging in any activity that constitutes or encourages conduct that would constitute a criminal offense, give rise to civil liability, or otherwise violate any applicable law or regulations
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: To use the Trellis Platform, the Customer may be required to complete a Know Your Customer (KYC) process.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Trellis
provenance_date: '2026-11-10'
provider_name: Trellis
provider_slug: trellistech
slug: trellistech-eligibility
source_date: '2026-11-10'
source_filename: trellistech-eligibility.yml
source_heading: Eligibility
source_page: https://www.trellistech.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Trellis\naid: trellistech\nurl: https://www.trellistech.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Acceptable use restrictions\n  text: Engaging in any activity that constitutes or encourages conduct that would constitute a criminal offense,\n    give rise to civil liability, or otherwise violate any applicable law or regulations\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: To use the Trellis Platform, the Customer may be required to complete a Know Your Customer (KYC) process.\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/trellistech/eligibility/trellistech-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Trellis's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Property Management
- Vacation Rentals
- Short-Term Rental
- AI Agents
- Hospitality
- Task Management
- MCP
---
