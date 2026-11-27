---
api_specs:
- filename: polygonscan-polygonscan-api-api-openapi.yml
  format: yaml
  label: PolygonScan PolygonScan API
  slug: polygonscan-polygonscan-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polygonscan/openapi/polygonscan-polygonscan-api-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'You represent and warrant that you: (a) are of legal age to form a binding contract'
    type: individual
  - text: If you are registering to use the Services on behalf of a legal entity, you further represent and warrant that (i) such legal entity is duly organized and validly existing
    type: business
  minimum_age:
    text: are of legal age to form a binding contract
    value: null
  restricted_uses:
  - summary: Illegal activity
    text: Use our Services to pay for, support or otherwise engage in any illegal activities, including, but not limited to illegal gambling, fraud, money-laundering, or terrorist activities
  - source: https://polygonscan.com/apiterms
    summary: Illegal activities and money laundering
    text: You are prohibited from using our API Services for any illegal activities or purposes, including but not limited to money laundering, corruption, or any actions that facilitate or promote such activities.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must create an account with Company to access the Services
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: PolygonScan
provenance_date: '2026-11-10'
provider_name: PolygonScan
provider_slug: polygonscan
slug: polygonscan-eligibility
source_date: '2026-11-10'
source_filename: polygonscan-eligibility.yml
source_heading: Eligibility
source_page: https://polygonscan.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PolygonScan\naid: polygonscan\nurl: https://polygonscan.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://polygonscan.com/apiterms\n  - https://polygonscan.com/terms\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'You represent and warrant that you: (a) are of legal age to form a binding contract'\n- type: business\n  text: If you are registering to use the Services on behalf of a legal entity, you further represent and warrant\n    that (i) such legal entity is duly organized and validly existing\nrestricted_uses:\n- summary: Illegal activity\n\
  \  text: Use our Services to pay for, support or otherwise engage in any illegal activities, including, but not limited\n    to illegal gambling, fraud, money-laundering, or terrorist activities\n- summary: Illegal activities and money laundering\n  text: You are prohibited from using our API Services for any illegal activities or purposes, including but not\n    limited to money laundering, corruption, or any actions that facilitate or promote such activities.\n  source: https://polygonscan.com/apiterms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must create an account with Company to access the Services\nminimum_age:\n  value: null\n  text: are of legal age to form a binding contract\n"
source_yaml_url: https://artifacts.apis.io/polygonscan/eligibility/polygonscan-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from PolygonScan's own page on 2026-11-10.
synthetic: false
tags:
- Blockchain
- Polygon
- Explorer
- Web3
- EVM
- Smart Contracts
- DeFi
- Cryptocurrency
---
