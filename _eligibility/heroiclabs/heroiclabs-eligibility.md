---
api_specs:
- filename: heroiclabs-nakama-api-openapi.yml
  format: yaml
  label: Nakama API
  slug: nakama-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/heroiclabs/openapi/heroiclabs-nakama-api-openapi.yml
- filename: heroiclabs-console-api-openapi.yml
  format: yaml
  label: Heroic Labs Console API
  slug: heroiclabs-console-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/heroiclabs/openapi/heroiclabs-console-api-openapi.yml
- filename: heroiclabs-rpc-api-openapi.yml
  format: yaml
  label: Heroic Labs Rpc API
  slug: heroiclabs-rpc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/heroiclabs/openapi/heroiclabs-rpc-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Services if You are a person barred from receiving the Services under the laws of the United States or other countries, including the country in which You are resident or from which You use the Services.
  entity_types:
  - text: If You are entering into these Terms on behalf of a company or other legal entity, You represent that You have the legal authority to bind it to these Terms
    type: business
  minimum_age:
    text: You hereby affirm that You are over the age of thirteen (13), as the Services are not intended for anyone under 13.
    value: '13'
  restricted_uses:
  - summary: Gambling without consent
    text: use the Services for any purpose that constitutes gambling without Heroic's prior written consent
  - summary: Cryptocurrency mining
    text: use the Services to "mine" bitcoins and other cryptocurrencies
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
name: Heroic Labs
provenance_date: '2026-11-09'
provider_name: Heroic Labs
provider_slug: heroiclabs
slug: heroiclabs-eligibility
source_date: '2026-11-09'
source_filename: heroiclabs-eligibility.yml
source_heading: Eligibility
source_page: https://heroiclabs.com/tos.txt
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Heroic Labs\naid: heroiclabs\nurl: https://heroiclabs.com/tos.txt\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Services if You are a person barred from receiving the Services under the laws of the\n    United States or other countries, including the country in which You are resident or from which You use the\n    Services.\nentity_types:\n- type: business\n  text: If You are entering into these Terms on behalf of a company or other legal entity, You represent that You\n    have the legal authority to bind it to these Terms\nrestricted_uses:\n- summary: Gambling\
  \ without consent\n  text: use the Services for any purpose that constitutes gambling without Heroic's prior written consent\n- summary: Cryptocurrency mining\n  text: use the Services to \"mine\" bitcoins and other cryptocurrencies\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You hereby affirm that You are over the age of thirteen (13), as the Services are not intended for anyone\n    under 13.\n"
source_yaml_url: https://artifacts.apis.io/heroiclabs/eligibility/heroiclabs-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Heroic Labs's own page on 2026-11-09.
synthetic: false
tags:
- Game Backend
- Multiplayer
- Real-Time
- WebSocket
- Matchmaking
- Leaderboards
- Social Gaming
- Open Source
- LiveOps
- gRPC
---
