---
api_specs:
- filename: walrus-protocol-routes-api-openapi.yml
  format: yaml
  label: Walrus Protocol Routes API
  slug: walrus-protocol-routes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/walrus-protocol/openapi/walrus-protocol-routes-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - BY
    - RU
    served: []
    text: you are not in or residing in Cuba, Iran, North Korea, Belarus, Russia, and the Crimea, Luhansk, Donetsk, Zaporizhzhia, and Kherson regions of Ukraine
  entity_types:
  - text: if you are entering into these Terms as an individual, then you are of legal age in the jurisdiction in which you reside
    type: individual
  - text: if you are entering into these Terms as an entity, then you must have the legal authority to accept these Terms on that entity's behalf
    type: business
  minimum_age:
    text: at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Sanctioned persons
    text: you are not on any sanctions list or equivalent maintained by the Cayman Islands, the United Kingdom, United States, the United Nations Security Council, or the European Union
  - summary: Circumventing geographic restrictions
    text: You must not use any software or networking techniques, including use of a virtual private network ("VPN") to circumvent or attempt to circumvent this prohibition.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may require information to verify your identity, your location, or your authority to act for an entity, and we may decline, suspend, or close an account where that information is not provided or where verification is unsuccessful.
excluded_countries:
- CU
- IR
- KP
- BY
- RU
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Walrus Protocol
provenance_date: '2026-11-10'
provider_name: Walrus Protocol
provider_slug: walrus-protocol
slug: walrus-protocol-eligibility
source_date: '2026-11-10'
source_filename: walrus-protocol-eligibility.yml
source_heading: Eligibility
source_page: https://docs.wal.app/docs/legal/walrus_general_tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Walrus Protocol\naid: walrus-protocol\nurl: https://docs.wal.app/docs/legal/walrus_general_tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - BY\n  - RU\n  text: you are not in or residing in Cuba, Iran, North Korea, Belarus, Russia, and the Crimea, Luhansk, Donetsk,\n    Zaporizhzhia, and Kherson regions of Ukraine\nentity_types:\n- type: individual\n  text: if you are entering into these Terms as an individual, then you are of legal age in the jurisdiction in\n    which you reside\n- type: business\n  text: if you are entering into these Terms as an entity, then\
  \ you must have the legal authority to accept these\n    Terms on that entity's behalf\nrestricted_uses:\n- summary: Sanctioned persons\n  text: you are not on any sanctions list or equivalent maintained by the Cayman Islands, the United Kingdom, United\n    States, the United Nations Security Council, or the European Union\n- summary: Circumventing geographic restrictions\n  text: You must not use any software or networking techniques, including use of a virtual private network (\"VPN\")\n    to circumvent or attempt to circumvent this prohibition.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may require information to verify your identity, your location, or your authority to act for an entity,\n    and we may decline, suspend, or close an account where that information is not provided or where verification\n    is unsuccessful.\nminimum_age:\n  value: '18'\n  text: at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/walrus-protocol/eligibility/walrus-protocol-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Walrus Protocol's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Infrastructure
- Storage
- Decentralized Storage
- Blockchain
- Web3
- Data
- Artificial Intelligence
- Sui
---
