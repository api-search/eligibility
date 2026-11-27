---
api_specs:
- filename: lighter-account-api-openapi.yml
  format: yaml
  label: Lighter Account API
  slug: lighter-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lighter/openapi/lighter-account-api-openapi.yml
- filename: lighter-announcement-api-openapi.yml
  format: yaml
  label: Lighter Announcement API
  slug: lighter-announcement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lighter/openapi/lighter-announcement-api-openapi.yml
- filename: lighter-bridge-api-openapi.yml
  format: yaml
  label: Lighter Bridge API
  slug: lighter-bridge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lighter/openapi/lighter-bridge-api-openapi.yml
- filename: lighter-candlestick-api-openapi.yml
  format: yaml
  label: Lighter Candlestick API
  slug: lighter-candlestick-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lighter/openapi/lighter-candlestick-api-openapi.yml
- filename: lighter-funding-api-openapi.yml
  format: yaml
  label: Lighter Funding API
  slug: lighter-funding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lighter/openapi/lighter-funding-api-openapi.yml
- filename: lighter-info-api-openapi.yml
  format: yaml
  label: Lighter Info API
  slug: lighter-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lighter/openapi/lighter-info-api-openapi.yml
- filename: lighter-notification-api-openapi.yml
  format: yaml
  label: Lighter Notification API
  slug: lighter-notification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lighter/openapi/lighter-notification-api-openapi.yml
- filename: lighter-order-api-openapi.yml
  format: yaml
  label: Lighter Order API
  slug: lighter-order-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lighter/openapi/lighter-order-api-openapi.yml
- filename: lighter-referral-api-openapi.yml
  format: yaml
  label: Lighter Referral API
  slug: lighter-referral-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lighter/openapi/lighter-referral-api-openapi.yml
- filename: lighter-root-api-openapi.yml
  format: yaml
  label: Lighter Root API
  slug: lighter-root-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lighter/openapi/lighter-root-api-openapi.yml
- filename: lighter-tokenlist-api-openapi.yml
  format: yaml
  label: Lighter Tokenlist API
  slug: lighter-tokenlist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lighter/openapi/lighter-tokenlist-api-openapi.yml
- filename: lighter-transaction-api-openapi.yml
  format: yaml
  label: Lighter Transaction API
  slug: lighter-transaction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lighter/openapi/lighter-transaction-api-openapi.yml
- filename: lighter-event-api-openapi.yml
  format: yaml
  label: Lighter Event API
  slug: lighter-event-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lighter/openapi/lighter-event-api-openapi.yml
- filename: lighter-portfolio-api-openapi.yml
  format: yaml
  label: Lighter Portfolio API
  slug: lighter-portfolio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lighter/openapi/lighter-portfolio-api-openapi.yml
- filename: lighter-updown-api-openapi.yml
  format: yaml
  label: Lighter Updown API
  slug: lighter-updown-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lighter/openapi/lighter-updown-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded:
    - US
    - CA
    - GB
    - CN
    - KP
    - RU
    - UA
    - CU
    - IR
    - VE
    - SY
    - SD
    - BY
    - MM
    served: []
    text: OUR SERVICES WERE NOT DEVELOPED FOR, AND ARE NOT AVAILABLE TO PERSONS OR ENTITIES WHO RESIDE IN, ARE LOCATED IN, ARE INCORPORATED IN, OR HAVE A REGISTERED OFFICE OR PRINCIPAL PLACE OF BUSINESS IN THE UNITED STATES OF AMERICA, CANADA, THE UNITED KINGDOM, CHINA, NORTH KOREA, RUSSIA, UKRAINE, CUBA, IRAN, VENEZUELA, SUDAN, BELARUS, MYANMAR OR SYRIA.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned or Prohibited Persons barred
    text: You are not (a) the subject of economic or trade sanctions or otherwise on a list of prohibited or restricted parties
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- US
- CA
- GB
- CN
- KP
- RU
- UA
- CU
- IR
- VE
- SY
- SD
- BY
- MM
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Lighter
provenance_date: '2026-11-09'
provider_name: Lighter
provider_slug: lighter
slug: lighter-eligibility
source_date: '2026-11-09'
source_filename: lighter-eligibility.yml
source_heading: Eligibility
source_page: https://lighter.xyz/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lighter\naid: lighter\nurl: https://lighter.xyz/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - US\n  - CA\n  - GB\n  - CN\n  - KP\n  - RU\n  - UA\n  - CU\n  - IR\n  - VE\n  - SY\n  - SD\n  - BY\n  - MM\n  text: OUR SERVICES WERE NOT DEVELOPED FOR, AND ARE NOT AVAILABLE TO PERSONS OR ENTITIES WHO RESIDE IN, ARE LOCATED\n    IN, ARE INCORPORATED IN, OR HAVE A REGISTERED OFFICE OR PRINCIPAL PLACE OF BUSINESS IN THE UNITED STATES OF\n    AMERICA, CANADA, THE UNITED KINGDOM, CHINA, NORTH KOREA, RUSSIA, UKRAINE, CUBA, IRAN, VENEZUELA, SUDAN, BELARUS,\n    MYANMAR OR SYRIA.\nentity_types:\
  \ []\nrestricted_uses:\n- summary: Sanctioned or Prohibited Persons barred\n  text: You are not (a) the subject of economic or trade sanctions or otherwise on a list of prohibited or restricted\n    parties\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/lighter/eligibility/lighter-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Lighter's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Trading
- Cryptocurrency
- Decentralized Finance
- Perpetual Futures
- Exchange
- Blockchain
- Zero Knowledge
- Market Data
- WebSocket
- Real-Time
---
