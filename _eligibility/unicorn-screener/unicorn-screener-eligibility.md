---
api_specs:
- filename: unicorn-screener-agent-api-openapi.yml
  format: yaml
  label: Unicorn Screener Agent API
  slug: unicorn-screener-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unicorn-screener/openapi/unicorn-screener-agent-api-openapi.yml
- filename: unicorn-screener-autocomplete-api-openapi.yml
  format: yaml
  label: Unicorn Screener Autocomplete API
  slug: unicorn-screener-autocomplete-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unicorn-screener/openapi/unicorn-screener-autocomplete-api-openapi.yml
- filename: unicorn-screener-request-report-api-openapi.yml
  format: yaml
  label: Unicorn Screener Request Report API
  slug: unicorn-screener-request-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unicorn-screener/openapi/unicorn-screener-request-report-api-openapi.yml
- filename: unicorn-screener-screen-status-api-openapi.yml
  format: yaml
  label: Unicorn Screener Screen Status API
  slug: unicorn-screener-screen-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unicorn-screener/openapi/unicorn-screener-screen-status-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Use an account that meets LinkedIn's applicable minimum age and account rules.
    value: null
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
name: Unicorn Screener
provenance_date: '2026-11-10'
provider_name: Unicorn Screener
provider_slug: unicorn-screener
slug: unicorn-screener-eligibility
source_date: '2026-11-10'
source_filename: unicorn-screener-eligibility.yml
source_heading: Eligibility
source_page: https://unicornscreener.vc/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Unicorn Screener\naid: unicorn-screener\nurl: https://unicornscreener.vc/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: Use an account that meets LinkedIn's applicable minimum age and account rules.\n"
source_yaml_url: https://artifacts.apis.io/unicorn-screener/eligibility/unicorn-screener-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from Unicorn Screener's own page on 2026-11-10.
synthetic: false
tags:
- Venture Capital
- Startups
- Company Research
- Screening
- Investing
- AI Agents
---
