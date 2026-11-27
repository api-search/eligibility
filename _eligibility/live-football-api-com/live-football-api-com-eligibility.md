---
api_specs:
- filename: live-football-api-com-openapi-generated.yml
  format: yaml
  label: live-football-api-com API
  slug: live-football-api-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/live-football-api-com/openapi/_ae-authored/live-football-api-com-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and legally capable of entering a binding contract.
    type: individual
  - text: If you are acting on behalf of a company or organisation, you confirm that you have authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old and legally capable of entering a binding contract.
    value: '18'
  restricted_uses:
  - summary: Illegal purposes
    text: Use the Service for any illegal purpose or in violation of any applicable law or regulation.
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
name: live-football-api-com
provenance_date: '2026-11-09'
provider_name: live-football-api-com
provider_slug: live-football-api-com
slug: live-football-api-com-eligibility
source_date: '2026-11-09'
source_filename: live-football-api-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.live-football-api.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: live-football-api-com\naid: live-football-api-com\nurl: https://www.live-football-api.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and legally capable of entering a binding contract.\n- type: business\n  text: If you are acting on behalf of a company or organisation, you confirm that you have authority to bind that\n    entity to these Terms.\nrestricted_uses:\n- summary: Illegal purposes\n  text: Use the Service for any illegal purpose or in violation of any applicable law or regulation.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally capable of entering a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/live-football-api-com/eligibility/live-football-api-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from live-football-api-com's own page on 2026-11-09.
synthetic: false
tags:
- Sports
- Football
- Real-Time
- Data
---
