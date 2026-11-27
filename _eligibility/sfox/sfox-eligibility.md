---
api_specs:
- filename: rest-endpoints
  format: yaml
  label: sFOX REST API
  slug: sfox-rest-api
  spec_type: OpenAPI
  url: https://docs.sfox.com/rest-api/rest-endpoints
- filename: sfox-websocket-asyncapi.yml
  format: yaml
  label: sFOX WebSocket API
  slug: sfox-websocket-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/sfox/asyncapi/sfox-websocket-asyncapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: sFOX may not make all the Services available in all markets and jurisdictions and may restrict or prohibit use of all or a portion of the Services from certain countries, states, territories, or jurisdictions.
  entity_types:
  - text: You must be 18 years old to use the sFOX Site or the Services and represent that you are of such age in doing so.
    type: individual
  - text: If you are using the Services on behalf of a legal entity, you further represent and warrant that the legal entity is duly organized and validly existing
    type: business
  minimum_age:
    text: You must be 18 years old to use the sFOX Site or the Services
    value: '18'
  restricted_uses:
  - summary: Unlawful or undesirable activity
    text: including, but not limited to dealing in regulated products or services, pseudo-pharmaceuticals, adult content and services, unfair/predatory practices, counterfeit goods, gambling, suspected money laundering, or drug activity.
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: you may be required to provide sFOX with certain personal information, including, but not limited to, your name, address, telephone number, e-mail address, date of birth, taxpayer identification number, government identification number
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Sfox
provenance_date: '2026-11-10'
provider_name: Sfox
provider_slug: sfox
slug: sfox-eligibility
source_date: '2026-11-10'
source_filename: sfox-eligibility.yml
source_heading: Eligibility
source_page: https://www.sfox.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sfox\naid: sfox\nurl: https://www.sfox.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: sFOX may not make all the Services available in all markets and jurisdictions and may restrict or prohibit\n    use of all or a portion of the Services from certain countries, states, territories, or jurisdictions.\nentity_types:\n- type: individual\n  text: You must be 18 years old to use the sFOX Site or the Services and represent that you are of such age in\n    doing so.\n- type: business\n  text: If you are using the Services on behalf of a legal entity, you further\
  \ represent and warrant that the legal\n    entity is duly organized and validly existing\nrestricted_uses:\n- summary: Unlawful or undesirable activity\n  text: including, but not limited to dealing in regulated products or services, pseudo-pharmaceuticals, adult content\n    and services, unfair/predatory practices, counterfeit goods, gambling, suspected money laundering, or drug activity.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: you may be required to provide sFOX with certain personal information, including, but not limited to, your\n    name, address, telephone number, e-mail address, date of birth, taxpayer identification number, government identification\n    number\nminimum_age:\n  value: '18'\n  text: You must be 18 years old to use the sFOX Site or the Services\n"
source_yaml_url: https://artifacts.apis.io/sfox/eligibility/sfox-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Sfox's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cryptocurrency
- Prime Brokerage
- Trading
- Digital Asset Custody
- Liquidity
- Staking
- Institutional
- Financial Services
- Market Data
- WebSocket
- FIX
- Real-Time
---
