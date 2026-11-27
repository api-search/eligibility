---
api_specs:
- filename: dmarket-account-api-openapi.yml
  format: yaml
  label: DMarket Account API
  slug: dmarket-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dmarket/openapi/dmarket-account-api-openapi.yml
- filename: dmarket-aggregator-api-openapi.yml
  format: yaml
  label: DMarket Aggregator API
  slug: dmarket-aggregator-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dmarket/openapi/dmarket-aggregator-api-openapi.yml
- filename: dmarket-buy-items-api-openapi.yml
  format: yaml
  label: DMarket Buy items API
  slug: dmarket-buy-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dmarket/openapi/dmarket-buy-items-api-openapi.yml
- filename: dmarket-inventory-items-api-openapi.yml
  format: yaml
  label: DMarket Inventory/items API
  slug: dmarket-inventory-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dmarket/openapi/dmarket-inventory-items-api-openapi.yml
- filename: dmarket-sell-items-api-openapi.yml
  format: yaml
  label: DMarket Sell Items API
  slug: dmarket-sell-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dmarket/openapi/dmarket-sell-items-api-openapi.yml
- filename: dmarket-sold-user-items-api-openapi.yml
  format: yaml
  label: DMarket Sold user items API
  slug: dmarket-sold-user-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dmarket/openapi/dmarket-sold-user-items-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - RU
    - BY
    served: []
    text: DMarket reserves its right to prohibit without any compensations or explanations access to the Website and/or Service of any residents ... (e) or persons from the Russian Federation and/or the Republic of Belarus.
  entity_types:
  - text: if You are a corporation, governmental organization or other legal entity, You have the right, power and authority to act on behalf of such corporation, governmental organization or other legal entity and bind them to these Terms
    type: business
  minimum_age:
    text: You are of an age of majority in the jurisdiction where You are a resident (at least 18 years of age)
    value: '18'
  restricted_uses:
  - summary: Gambling-related activity flagged as suspicious
    text: User is directly or indirectly engages, facilitates or advertises online and offline gambling activities
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: If You intend to deposit funds through VISA/Mastercard, You will have to complete KYC procedure. It needs to be completed just once.
excluded_countries:
- RU
- BY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: DMarket
provenance_date: '2026-11-09'
provider_name: DMarket
provider_slug: dmarket
slug: dmarket-eligibility
source_date: '2026-11-09'
source_filename: dmarket-eligibility.yml
source_heading: Eligibility
source_page: https://dmarket.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DMarket\naid: dmarket\nurl: https://dmarket.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - RU\n  - BY\n  text: DMarket reserves its right to prohibit without any compensations or explanations access to the Website and/or\n    Service of any residents ... (e) or persons from the Russian Federation and/or the Republic of Belarus.\nentity_types:\n- type: business\n  text: if You are a corporation, governmental organization or other legal entity, You have the right, power and\n    authority to act on behalf of such corporation, governmental organization or other legal entity\
  \ and bind them\n    to these Terms\nrestricted_uses:\n- summary: Gambling-related activity flagged as suspicious\n  text: User is directly or indirectly engages, facilitates or advertises online and offline gambling activities\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: If You intend to deposit funds through VISA/Mastercard, You will have to complete KYC procedure. It needs\n    to be completed just once.\nminimum_age:\n  value: '18'\n  text: You are of an age of majority in the jurisdiction where You are a resident (at least 18 years of age)\n"
source_yaml_url: https://artifacts.apis.io/dmarket/eligibility/dmarket-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from DMarket's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Gaming
- Marketplace
- Trading
- Skins
- In-Game Items
- Blockchain
---
