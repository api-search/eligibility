---
api_specs:
- filename: geekflare-api-tool-api-openapi.yml
  format: yaml
  label: Geekflare API Tool API
  slug: geekflare-api-tool-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geekflare/openapi/geekflare-api-tool-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use any Geekflare Service if you are the subject of U.S. sanctions or of sanctions consistent with U.S. law imposed by the governments of the country where you are using the Services.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned users
    text: You may not use any Geekflare Service if you are the subject of U.S. sanctions
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
name: Geekflare
provenance_date: '2026-11-09'
provider_name: Geekflare
provider_slug: geekflare
slug: geekflare-eligibility
source_date: '2026-11-09'
source_filename: geekflare-eligibility.yml
source_heading: Eligibility
source_page: https://geekflare.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Geekflare\naid: geekflare\nurl: https://geekflare.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use any Geekflare Service if you are the subject of U.S. sanctions or of sanctions consistent\n    with U.S. law imposed by the governments of the country where you are using the Services.\nentity_types: []\nrestricted_uses:\n- summary: Sanctioned users\n  text: You may not use any Geekflare Service if you are the subject of U.S. sanctions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/geekflare/eligibility/geekflare-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Geekflare's own page on 2026-11-09.
synthetic: false
tags:
- Development
- Public APIs
- Web Scraping
- Search
- Screenshots
- DNS
- Website Monitoring
- Security Testing
- AI Agents
- MCP
---
