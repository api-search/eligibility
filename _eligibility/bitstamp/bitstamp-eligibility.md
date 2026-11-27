---
api_specs:
- filename: bitstamp-market-data-api-openapi.yml
  format: yaml
  label: Bitstamp Market Data API
  slug: bitstamp-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitstamp/openapi/bitstamp-market-data-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - CA
    served: []
    text: As of March 24, 2023, residents of Canada are not permitted to open new accounts on the Site.
  entity_types:
  - text: If you are an individual, that you are at least 18 years of age
    type: individual
  - text: If you are a legal entity or acting in the name of a legal entity, that you are duly authorised to act on behalf and in the name of the legal entity, and bind the latter validly
    type: business
  minimum_age:
    text: If you are an individual, that you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Personal use only unless corporate account
    text: You will refrain from using your Account, the Site and Services for any other use than your personal use, unless you are a legal entity that has opened a corporate account with us.
  - summary: Criminal activity
    text: You agree not to use the Services to perform criminal activity of any sort, including but not limited to, money laundering, illegal gambling operations, terrorist financing, malicious hacking or any criminal or illegal activity.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CA
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bitstamp
provenance_date: '2026-11-09'
provider_name: Bitstamp
provider_slug: bitstamp
slug: bitstamp-eligibility
source_date: '2026-11-09'
source_filename: bitstamp-eligibility.yml
source_heading: Eligibility
source_page: https://www.bitstamp.net/legal/terms-of-use/ltd/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bitstamp\naid: bitstamp\nurl: https://www.bitstamp.net/legal/terms-of-use/ltd/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - CA\n  text: As of March 24, 2023, residents of Canada are not permitted to open new accounts on the Site.\nentity_types:\n- type: individual\n  text: If you are an individual, that you are at least 18 years of age\n- type: business\n  text: If you are a legal entity or acting in the name of a legal entity, that you are duly authorised to act on\n    behalf and in the name of the legal entity, and bind the latter validly\nrestricted_uses:\n- summary:\
  \ Personal use only unless corporate account\n  text: You will refrain from using your Account, the Site and Services for any other use than your personal use,\n    unless you are a legal entity that has opened a corporate account with us.\n- summary: Criminal activity\n  text: You agree not to use the Services to perform criminal activity of any sort, including but not limited to,\n    money laundering, illegal gambling operations, terrorist financing, malicious hacking or any criminal or illegal\n    activity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are an individual, that you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/bitstamp/eligibility/bitstamp-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Bitstamp's own page on 2026-11-09.
synthetic: false
tags:
- Cryptocurrency
- Exchange
- Trading
- Bitcoin
- Ethereum
- Spot Trading
- WebSocket
- Market Data
- Order Management
- Finance
---
