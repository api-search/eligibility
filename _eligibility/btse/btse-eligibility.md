---
api_specs:
- filename: btse-account-api-openapi.yml
  format: yaml
  label: BTSE Account API
  slug: btse-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/btse/openapi/btse-account-api-openapi.yml
- filename: btse-earn-api-openapi.yml
  format: yaml
  label: BTSE Earn API
  slug: btse-earn-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/btse/openapi/btse-earn-api-openapi.yml
- filename: btse-markets-api-openapi.yml
  format: yaml
  label: BTSE Markets API
  slug: btse-markets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/btse/openapi/btse-markets-api-openapi.yml
- filename: btse-otc-api-openapi.yml
  format: yaml
  label: BTSE OTC API
  slug: btse-otc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/btse/openapi/btse-otc-api-openapi.yml
- filename: btse-trade-api-openapi.yml
  format: yaml
  label: BTSE Trade API
  slug: btse-trade-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/btse/openapi/btse-trade-api-openapi.yml
- filename: btse-trade-v3-api-openapi.yml
  format: yaml
  label: BTSE Trade V3 API
  slug: btse-trade-v3-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/btse/openapi/btse-trade-v3-api-openapi.yml
- filename: btse-trade-v4-api-openapi.yml
  format: yaml
  label: BTSE Trade V4 API
  slug: btse-trade-v4-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/btse/openapi/btse-trade-v4-api-openapi.yml
- filename: btse-wallet-api-openapi.yml
  format: yaml
  label: BTSE Wallet API
  slug: btse-wallet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/btse/openapi/btse-wallet-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - US
    - CA
    - CU
    - IR
    - KP
    - SY
    - TW
    - RU
    - GB
    served: []
    text: The Services are not intended for use by individuals who are citizens or nationals of or resident in the United States of America, Canada, Cuba, Iran, North Korea, Syria, Taiwan, Russia, and the United Kingdom, among other jurisdictions
  entity_types:
  - text: the User is at least 18 years old
    type: individual
  - text: if one is registering on behalf of a legal entity
    type: business
  minimum_age:
    text: the User is at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Prohibited uses
    text: 'The User may not: use the Interface or Services to disguise the origin or nature of illicit proceeds'
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: During the registration process, the User may need to submit information and documents in order to verify
excluded_countries:
- US
- CA
- CU
- IR
- KP
- SY
- TW
- RU
- GB
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BTSE
provenance_date: '2026-11-09'
provider_name: BTSE
provider_slug: btse
slug: btse-eligibility
source_date: '2026-11-09'
source_filename: btse-eligibility.yml
source_heading: Eligibility
source_page: https://www.btse.com/en/termsandconditions?anchor=1
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BTSE\naid: btse\nurl: https://www.btse.com/en/termsandconditions?anchor=1\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - US\n  - CA\n  - CU\n  - IR\n  - KP\n  - SY\n  - TW\n  - RU\n  - GB\n  text: The Services are not intended for use by individuals who are citizens or nationals of or resident in the\n    United States of America, Canada, Cuba, Iran, North Korea, Syria, Taiwan, Russia, and the United Kingdom, among\n    other jurisdictions\nentity_types:\n- type: individual\n  text: the User is at least 18 years old\n- type: business\n  text: if one is registering on behalf of a legal\
  \ entity\nrestricted_uses:\n- summary: Prohibited uses\n  text: 'The User may not: use the Interface or Services to disguise the origin or nature of illicit proceeds'\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: During the registration process, the User may need to submit information and documents in order to verify\nminimum_age:\n  value: '18'\n  text: the User is at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/btse/eligibility/btse-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from BTSE's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Exchange
- Trading
- Digital Assets
- Futures
- WebSocket
---
