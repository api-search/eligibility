---
api_specs:
- filename: opplevagent-no-a2a-api-openapi.yml
  format: yaml
  label: Opplevagent A2a API
  slug: opplevagent-no-a2a-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opplevagent-no/openapi/opplevagent-no-a2a-api-openapi.yml
- filename: opplevagent-no-llms-txt-api-openapi.yml
  format: yaml
  label: Opplevagent Llms.txt API
  slug: opplevagent-no-llms-txt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opplevagent-no/openapi/opplevagent-no-llms-txt-api-openapi.yml
- filename: opplevagent-no-opplevelser-api-openapi.yml
  format: yaml
  label: Opplevagent Opplevelser API
  slug: opplevagent-no-opplevelser-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opplevagent-no/openapi/opplevagent-no-opplevelser-api-openapi.yml
- filename: opplevagent-no-well-known-api-openapi.yml
  format: yaml
  label: Opplevagent .well Known API
  slug: opplevagent-no-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opplevagent-no/openapi/opplevagent-no-well-known-api-openapi.yml
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
  - summary: No bulk spam to providers
    text: Bulk unsolicited messages or spam to providers.
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
name: Opplevagent
provenance_date: '2026-11-10'
provider_name: Opplevagent
provider_slug: opplevagent-no
slug: opplevagent-no-eligibility
source_date: '2026-11-10'
source_filename: opplevagent-no-eligibility.yml
source_heading: Eligibility
source_page: https://opplevagent.no/vilkar
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Opplevagent\naid: opplevagent-no\nurl: https://opplevagent.no/vilkar\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No bulk spam to providers\n  text: Bulk unsolicited messages or spam to providers.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/opplevagent-no/eligibility/opplevagent-no-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Opplevagent's own page on 2026-11-10.
synthetic: false
tags:
- Travel
- Tourism
- Experience
- Activities
- Norway
- Marketplace
- Agent-Native
- A2A
- MCP
- Booking
- Local Food
- Open Data
---
