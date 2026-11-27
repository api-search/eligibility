---
api_specs:
- filename: chinaready-co-assistant-api-openapi.yml
  format: yaml
  label: Chinaready Assistant API
  slug: chinaready-co-assistant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chinaready-co/openapi/chinaready-co-assistant-api-openapi.yml
- filename: chinaready-co-contact-api-openapi.yml
  format: yaml
  label: Chinaready Contact API
  slug: chinaready-co-contact-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chinaready-co/openapi/chinaready-co-contact-api-openapi.yml
- filename: chinaready-co-intake-api-openapi.yml
  format: yaml
  label: Chinaready Intake API
  slug: chinaready-co-intake-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chinaready-co/openapi/chinaready-co-intake-api-openapi.yml
- filename: chinaready-co-search-api-openapi.yml
  format: yaml
  label: Chinaready Search API
  slug: chinaready-co-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chinaready-co/openapi/chinaready-co-search-api-openapi.yml
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
  - summary: Diagnostics on unauthorized properties
    text: Diagnostics tools may only be used against properties you own or are authorized to test.
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
name: Chinaready
provenance_date: '2026-11-09'
provider_name: Chinaready
provider_slug: chinaready-co
slug: chinaready-co-eligibility
source_date: '2026-11-09'
source_filename: chinaready-co-eligibility.yml
source_heading: Eligibility
source_page: https://chinaready.co/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chinaready\naid: chinaready-co\nurl: https://chinaready.co/legal/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Diagnostics on unauthorized properties\n  text: Diagnostics tools may only be used against properties you own or are authorized to test.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chinaready-co/eligibility/chinaready-co-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Chinaready's own page on 2026-11-09.
synthetic: false
tags:
- Company
- China
- Market Entry
- Content Delivery
- Hosting
- Compliance
- Mobile App Distribution
- Network Diagnostics
- MCP
---
