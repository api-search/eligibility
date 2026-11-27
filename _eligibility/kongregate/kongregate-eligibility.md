---
api_specs:
- filename: kongregate-authenticate-json-api-openapi.yml
  format: yaml
  label: Kongregate Authenticate.json API
  slug: kongregate-authenticate-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kongregate/openapi/kongregate-authenticate-json-api-openapi.yml
- filename: kongregate-characters-json-api-openapi.yml
  format: yaml
  label: Kongregate Characters.json API
  slug: kongregate-characters-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kongregate/openapi/kongregate-characters-json-api-openapi.yml
- filename: kongregate-guilds-api-openapi.yml
  format: yaml
  label: Kongregate Guilds API
  slug: kongregate-guilds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kongregate/openapi/kongregate-guilds-api-openapi.yml
- filename: kongregate-guilds-json-api-openapi.yml
  format: yaml
  label: Kongregate Guilds.json API
  slug: kongregate-guilds-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kongregate/openapi/kongregate-guilds-json-api-openapi.yml
- filename: kongregate-high-scores-api-openapi.yml
  format: yaml
  label: Kongregate High Scores API
  slug: kongregate-high-scores-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kongregate/openapi/kongregate-high-scores-api-openapi.yml
- filename: kongregate-items-json-api-openapi.yml
  format: yaml
  label: Kongregate Items.json API
  slug: kongregate-items-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kongregate/openapi/kongregate-items-json-api-openapi.yml
- filename: kongregate-kongpanions-api-openapi.yml
  format: yaml
  label: Kongregate Kongpanions API
  slug: kongregate-kongpanions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kongregate/openapi/kongregate-kongpanions-api-openapi.yml
- filename: kongregate-kongpanions-json-api-openapi.yml
  format: yaml
  label: Kongregate Kongpanions.json API
  slug: kongregate-kongpanions-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kongregate/openapi/kongregate-kongpanions-json-api-openapi.yml
- filename: kongregate-shared-links-api-openapi.yml
  format: yaml
  label: Kongregate Shared Links API
  slug: kongregate-shared-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kongregate/openapi/kongregate-shared-links-api-openapi.yml
- filename: kongregate-submit-statistics-json-api-openapi.yml
  format: yaml
  label: Kongregate Submit Statistics.json API
  slug: kongregate-submit-statistics-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kongregate/openapi/kongregate-submit-statistics-json-api-openapi.yml
- filename: kongregate-use-item-json-api-openapi.yml
  format: yaml
  label: Kongregate Use Item.json API
  slug: kongregate-use-item-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kongregate/openapi/kongregate-use-item-json-api-openapi.yml
- filename: kongregate-user-info-json-api-openapi.yml
  format: yaml
  label: Kongregate User Info.json API
  slug: kongregate-user-info-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kongregate/openapi/kongregate-user-info-json-api-openapi.yml
- filename: kongregate-user-items-json-api-openapi.yml
  format: yaml
  label: Kongregate User Items.json API
  slug: kongregate-user-items-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kongregate/openapi/kongregate-user-items-json-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - US
    served: []
    text: (C) for use of Services related to blockchain, you (i) have access to a digital wallet ... (b) do not reside in a country that is banned or sanctioned by the United States Department of the Treasury’s Office of Foreign Assets Control
  entity_types:
  - text: Our Services are designed for and directed at people 18 years of age or older.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Blockchain/NFT use restricted by sanctions
    text: do not appear on the U.S. Department of the Treasury’s Specifically Designated Nationals list, (b) do not reside in a country that is banned or sanctioned by the United States Department of the Treasury’s Office of Foreign Assets Control
  - summary: Virtual Items not for resale or transfer
    text: You may not transfer, assign, sell, gift, exchange, trade, convert, lease, sublease, rent, or distribute Virtual Items except as expressly permitted by us or in these Terms.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- US
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Kongregate
provenance_date: '2026-11-09'
provider_name: Kongregate
provider_slug: kongregate
slug: kongregate-eligibility
source_date: '2026-11-09'
source_filename: kongregate-eligibility.yml
source_heading: Eligibility
source_page: https://www.kongregate.com/en/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kongregate\naid: kongregate\nurl: https://www.kongregate.com/en/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - US\n  text: (C) for use of Services related to blockchain, you (i) have access to a digital wallet ... (b) do not reside\n    in a country that is banned or sanctioned by the United States Department of the Treasury’s Office of Foreign\n    Assets Control\nentity_types:\n- type: individual\n  text: Our Services are designed for and directed at people 18 years of age or older.\nrestricted_uses:\n- summary: Blockchain/NFT use restricted by sanctions\n\
  \  text: do not appear on the U.S. Department of the Treasury’s Specifically Designated Nationals list, (b) do not\n    reside in a country that is banned or sanctioned by the United States Department of the Treasury’s Office of\n    Foreign Assets Control\n- summary: Virtual Items not for resale or transfer\n  text: You may not transfer, assign, sell, gift, exchange, trade, convert, lease, sublease, rent, or distribute\n    Virtual Items except as expressly permitted by us or in these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kongregate/eligibility/kongregate-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Kongregate's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Gaming
- Games
- Game Development
- Browser Games
- Virtual Goods
- Microtransactions
- Leaderboards
- Player Identity
- Unity
- Developer Platform
---
