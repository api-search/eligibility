---
api_specs:
- filename: sitey-my-check-api-openapi.yml
  format: yaml
  label: sitey-my Check API
  slug: sitey-my-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sitey-my/openapi/sitey-my-check-api-openapi.yml
- filename: sitey-my-domains-api-openapi.yml
  format: yaml
  label: sitey-my Domains API
  slug: sitey-my-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sitey-my/openapi/sitey-my-domains-api-openapi.yml
- filename: sitey-my-subdomains-api-openapi.yml
  format: yaml
  label: sitey-my Subdomains API
  slug: sitey-my-subdomains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sitey-my/openapi/sitey-my-subdomains-api-openapi.yml
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
  - summary: Account-only features
    text: TXT records Pointing a name at a temporary tunnel (trycloudflare.com, ngrok and the like) Names containing words such as login , wallet or verify
  - summary: Well-known brand names refused
    text: Names containing the names of well-known brands (banks, exchanges, big platforms) are refused for everyone.
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
name: sitey-my
provenance_date: '2026-11-10'
provider_name: sitey-my
provider_slug: sitey-my
slug: sitey-my-eligibility
source_date: '2026-11-10'
source_filename: sitey-my-eligibility.yml
source_heading: Eligibility
source_page: https://sitey.my/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: sitey-my\naid: sitey-my\nurl: https://sitey.my/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Account-only features\n  text: TXT records Pointing a name at a temporary tunnel (trycloudflare.com, ngrok and the like) Names containing\n    words such as login , wallet or verify\n- summary: Well-known brand names refused\n  text: Names containing the names of well-known brands (banks, exchanges, big platforms) are refused for everyone.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sitey-my/eligibility/sitey-my-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from sitey-my's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Website Builder
- Sub Domain
- MCP
---
