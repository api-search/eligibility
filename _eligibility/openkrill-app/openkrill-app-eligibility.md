---
api_specs:
- filename: openkrill-app-openapi-generated.yml
  format: yaml
  label: openkrill-app API
  slug: openkrill-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openkrill-app/openapi/_ae-authored/openkrill-app-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Recall Check and Car Check cover the United States only. Travel Check reports UK and US government advice.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful use
    text: Do not use the plugins or the API to overload them or the job boards behind them, to get around their rate limits, or for anything unlawful.
  - summary: Personal information
    text: Do not send it personal information.
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
name: openkrill-app
provenance_date: '2026-11-10'
provider_name: openkrill-app
provider_slug: openkrill-app
slug: openkrill-app-eligibility
source_date: '2026-11-10'
source_filename: openkrill-app-eligibility.yml
source_heading: Eligibility
source_page: https://tools.openkrill.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: openkrill-app\naid: openkrill-app\nurl: https://tools.openkrill.app/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Recall Check and Car Check cover the United States only. Travel Check reports UK and US government advice.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful use\n  text: Do not use the plugins or the API to overload them or the job boards behind them, to get around their rate\n    limits, or for anything unlawful.\n- summary: Personal information\n  text: Do not send it personal information.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/openkrill-app/eligibility/openkrill-app-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from openkrill-app's own page on 2026-11-10.
synthetic: false
tags:
- Company
- MarineBiology
- Data Analytics
- EnvironmentalResearch
- Open Data
---
