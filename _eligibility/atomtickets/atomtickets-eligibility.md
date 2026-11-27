---
api_specs:
- filename: atomtickets-partner-api-openapi.yml
  format: yaml
  label: Atomtickets Partner API
  slug: atomtickets-partner-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atomtickets/openapi/atomtickets-partner-api-openapi.yml
- filename: atomtickets-partner-api-openapi.yml
  format: yaml
  label: Atomtickets Partner API
  slug: atomtickets-partner-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atomtickets/openapi/atomtickets-partner-api-openapi.yml
- filename: atomtickets-ping-api-openapi.yml
  format: yaml
  label: Atomtickets Ping API
  slug: atomtickets-ping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atomtickets/openapi/atomtickets-ping-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You represent that You are (1) at least thirteen (13) years old
    value: '13'
  restricted_uses:
  - summary: Commercial use of the service
    text: Use the Atom Tickets Properties or any part thereof for any commercial purpose
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
name: Atomtickets
provenance_date: '2026-11-09'
provider_name: Atomtickets
provider_slug: atomtickets
slug: atomtickets-eligibility
source_date: '2026-11-09'
source_filename: atomtickets-eligibility.yml
source_heading: Eligibility
source_page: https://www.atomtickets.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Atomtickets\naid: atomtickets\nurl: https://www.atomtickets.com/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Commercial use of the service\n  text: Use the Atom Tickets Properties or any part thereof for any commercial purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You represent that You are (1) at least thirteen (13) years old\n"
source_yaml_url: https://artifacts.apis.io/atomtickets/eligibility/atomtickets-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Atomtickets's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Ticketing
- Event
- Payments
---
