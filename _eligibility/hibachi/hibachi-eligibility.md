---
api_specs:
- filename: hibachi-capital-api-openapi.yml
  format: yaml
  label: Hibachi Capital API
  slug: hibachi-capital-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hibachi/openapi/hibachi-capital-api-openapi.yml
- filename: hibachi-market-api-openapi.yml
  format: yaml
  label: Hibachi Market API
  slug: hibachi-market-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hibachi/openapi/hibachi-market-api-openapi.yml
- filename: hibachi-trade-api-openapi.yml
  format: yaml
  label: Hibachi Trade API
  slug: hibachi-trade-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hibachi/openapi/hibachi-trade-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - US
    - GB
    - IR
    - CU
    - KP
    - SY
    - MM
    served: []
    text: THE HIBACHI INTERFACE (AS DEFINED BELOW) IS NOT AVAILABLE TO PERSONS OR ENTITIES WHO RESIDE IN, ARE LOCATED IN, ARE INCORPORATED IN, OR HAVE A REGISTERED OFFICE IN THE UNITED STATES OF AMERICA OR UNITED KINGDOM
  entity_types:
  - text: if you are entering into these Terms as an individual, then you are of legal age in the jurisdiction in which you reside and you have the legal capacity to enter into these Terms
    type: individual
  minimum_age:
    text: if you are entering into these Terms as an individual, then you are of legal age in the jurisdiction in which you reside
    value: null
  restricted_uses:
  - summary: No Blocked Person may enter Perpetual Contracts
    text: no Blocked Person may enter into Perpetual Contracts using the Services
  - summary: Restricted territories excluded
    text: you must not be a resident, citizen or agent of, or incorporated in, and do not have a registered office in Iran, Cuba, North Korea, Syria, Myanmar (Burma)
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- US
- GB
- IR
- CU
- KP
- SY
- MM
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Hibachi
provenance_date: '2026-11-09'
provider_name: Hibachi
provider_slug: hibachi
slug: hibachi-eligibility
source_date: '2026-11-09'
source_filename: hibachi-eligibility.yml
source_heading: Eligibility
source_page: https://hibachi.xyz/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hibachi\naid: hibachi\nurl: https://hibachi.xyz/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - US\n  - GB\n  - IR\n  - CU\n  - KP\n  - SY\n  - MM\n  text: THE HIBACHI INTERFACE (AS DEFINED BELOW) IS NOT AVAILABLE TO PERSONS OR ENTITIES WHO RESIDE IN, ARE LOCATED\n    IN, ARE INCORPORATED IN, OR HAVE A REGISTERED OFFICE IN THE UNITED STATES OF AMERICA OR UNITED KINGDOM\nentity_types:\n- type: individual\n  text: if you are entering into these Terms as an individual, then you are of legal age in the jurisdiction in\n    which you reside and you have the legal capacity to enter into\
  \ these Terms\nrestricted_uses:\n- summary: No Blocked Person may enter Perpetual Contracts\n  text: no Blocked Person may enter into Perpetual Contracts using the Services\n- summary: Restricted territories excluded\n  text: you must not be a resident, citizen or agent of, or incorporated in, and do not have a registered office\n    in Iran, Cuba, North Korea, Syria, Myanmar (Burma)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: if you are entering into these Terms as an individual, then you are of legal age in the jurisdiction in\n    which you reside\n"
source_yaml_url: https://artifacts.apis.io/hibachi/eligibility/hibachi-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Hibachi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- DeFi
- Cryptocurrency
- Exchange
- Perpetual Futures
- Trading
- Derivatives
- Stablecoins
- WebSocket
- Blockchain
- Real-Time
---
