---
api_specs:
- filename: qfex-mds-asyncapi.yml
  format: yaml
  label: QFEX Market Data WebSocket (MDS)
  slug: qfex-market-data-websocket-mds
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/qfex/asyncapi/qfex-mds-asyncapi.yml
- filename: qfex-trade-asyncapi.yml
  format: yaml
  label: QFEX Trade WebSocket
  slug: qfex-trade-websocket
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/qfex/asyncapi/qfex-trade-asyncapi.yml
- filename: qfex-market-data-api-openapi.yml
  format: yaml
  label: Qfex Market Data API
  slug: qfex-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qfex/openapi/qfex-market-data-api-openapi.yml
- filename: qfex-pnl-api-openapi.yml
  format: yaml
  label: Qfex Pnl API
  slug: qfex-pnl-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qfex/openapi/qfex-pnl-api-openapi.yml
- filename: qfex-user-api-openapi.yml
  format: yaml
  label: Qfex User API
  slug: qfex-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qfex/openapi/qfex-user-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded:
    - US
    - CU
    - IR
    - KP
    - SY
    - RU
    served: []
    text: THE SERVICES WERE NOT DEVELOPED FOR, AND ARE NOT OFFERED TO PERSONS OR ENTITIES WHO RESIDE IN, ARE CITIZENS OF, ARE LOCATED IN, ARE INCORPORATED IN, OR HAVE A REGISTERED OFFICE OR PRINCIPAL PLACE OF BUSINESS IN THE UNITED STATES OR ANY RESTRICTED JURISDICTION. Restricted jurisdictions include THE CRIMEA REGION, CUBA, IRAN, NORTH KOREA, SYRIA, RUSSIA.
  entity_types:
  - text: These Services are offered and available to entities
    type: business
  - text: individual users who are 18 years of age or older
    type: individual
  minimum_age:
    text: individual users who are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Restricted persons and jurisdictions
    text: Transact on behalf of, or for the benefit of, any Restricted Person or any person or entity located in a Restricted Jurisdiction.
  - summary: Mixing or obscuring funds
    text: Use the Services as a mixer, tumbler, anonymization tool, or any other mechanism to obscure or disguise the source or destination of your funds.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Prior to using the Services to trade, you agree to subject yourself to “know your customer” screenings, and to provide us with all information we request to perform such screenings.
excluded_countries:
- US
- CU
- IR
- KP
- SY
- RU
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Qfex
provenance_date: '2026-11-10'
provider_name: Qfex
provider_slug: qfex
slug: qfex-eligibility
source_date: '2026-11-10'
source_filename: qfex-eligibility.yml
source_heading: Eligibility
source_page: https://docs.qfex.com/legal/client-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Qfex\naid: qfex\nurl: https://docs.qfex.com/legal/client-agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - US\n  - CU\n  - IR\n  - KP\n  - SY\n  - RU\n  text: THE SERVICES WERE NOT DEVELOPED FOR, AND ARE NOT OFFERED TO PERSONS OR ENTITIES WHO RESIDE IN, ARE CITIZENS\n    OF, ARE LOCATED IN, ARE INCORPORATED IN, OR HAVE A REGISTERED OFFICE OR PRINCIPAL PLACE OF BUSINESS IN THE UNITED\n    STATES OR ANY RESTRICTED JURISDICTION. Restricted jurisdictions include THE CRIMEA REGION, CUBA, IRAN, NORTH\n    KOREA, SYRIA, RUSSIA.\nentity_types:\n- type: business\n  text:\
  \ These Services are offered and available to entities\n- type: individual\n  text: individual users who are 18 years of age or older\nrestricted_uses:\n- summary: Restricted persons and jurisdictions\n  text: Transact on behalf of, or for the benefit of, any Restricted Person or any person or entity located in a\n    Restricted Jurisdiction.\n- summary: Mixing or obscuring funds\n  text: Use the Services as a mixer, tumbler, anonymization tool, or any other mechanism to obscure or disguise\n    the source or destination of your funds.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Prior to using the Services to trade, you agree to subject yourself to “know your customer” screenings,\n    and to provide us with all information we request to perform such screenings.\nminimum_age:\n  value: '18'\n  text: individual users who are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/qfex/eligibility/qfex-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Qfex's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Trading
- Exchange
- Perpetual Futures
- Market Data
- WebSocket
- Foreign Exchange
- Commodities
- Stocks
- Financial Services
- CLI
- Fintech
- Real-Time
---
