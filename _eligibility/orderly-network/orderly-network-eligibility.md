---
api_specs:
- filename: orderly-network-admin-api-openapi.yml
  format: yaml
  label: Orderly Network Admin API
  slug: orderly-network-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orderly-network/openapi/orderly-network-admin-api-openapi.yml
- filename: orderly-network-client-api-openapi.yml
  format: yaml
  label: Orderly Network Client API
  slug: orderly-network-client-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orderly-network/openapi/orderly-network-client-api-openapi.yml
- filename: orderly-network-private-api-openapi.yml
  format: yaml
  label: Orderly Network Private API
  slug: orderly-network-private-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orderly-network/openapi/orderly-network-private-api-openapi.yml
- filename: orderly-network-public-api-openapi.yml
  format: yaml
  label: Orderly Network Public API
  slug: orderly-network-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orderly-network/openapi/orderly-network-public-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - US
    - CU
    - KP
    - IR
    served: []
    text: By using our Services, you represent and warrant that you are not, or are acting on behalf of a US Person. (Cuba, Democratic People’s Republic of Korea, Iran named as sanctioned jurisdictions.)
  entity_types:
  - text: an individual user or site visitor, whether personally or on behalf of an entity
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Restricted Persons excluded
    text: For clarity, if you are a Restricted Person, you are prohibited from using any Service.
  - summary: Jurisdiction of residence only
    text: Participate in the Site from a jurisdiction other than the jurisdiction of your residence
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: we may conduct AML/CFT procedures, anti-fraud procedures, identity verification and authentication checks where applicable.
excluded_countries:
- US
- CU
- KP
- IR
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Orderly Network
provenance_date: '2026-11-10'
provider_name: Orderly Network
provider_slug: orderly-network
slug: orderly-network-eligibility
source_date: '2026-11-10'
source_filename: orderly-network-eligibility.yml
source_heading: Eligibility
source_page: https://orderly.network/docs/introduction/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Orderly Network\naid: orderly-network\nurl: https://orderly.network/docs/introduction/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - US\n  - CU\n  - KP\n  - IR\n  text: By using our Services, you represent and warrant that you are not, or are acting on behalf of a US Person.\n    (Cuba, Democratic People’s Republic of Korea, Iran named as sanctioned jurisdictions.)\nentity_types:\n- type: individual\n  text: an individual user or site visitor, whether personally or on behalf of an entity\nrestricted_uses:\n- summary: Restricted Persons excluded\n  text: For clarity, if\
  \ you are a Restricted Person, you are prohibited from using any Service.\n- summary: Jurisdiction of residence only\n  text: Participate in the Site from a jurisdiction other than the jurisdiction of your residence\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: we may conduct AML/CFT procedures, anti-fraud procedures, identity verification and authentication checks\n    where applicable.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/orderly-network/eligibility/orderly-network-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Orderly Network's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cryptocurrency
- DeFi
- Trading
- Perpetual Futures
- Derivatives
- Order Book
- Web3
- Blockchain
- Liquidity
- Real-Time
---
