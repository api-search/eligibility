---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service is only available to persons in eligible countries. You may not use the Service if you are located in, or a citizen or resident of, any other jurisdiction where ACINQ have determined to prohibit use of the Services
  entity_types:
  - text: Application is intended for use by persons who are very knowledgeable about cryptocurrency generally and non-custodial wallets in particular.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned countries and persons
    text: You are not permitted to use any of the Services if (1) you are a in, under the control of, or a national or resident of any country subject to sanctions by the United Nations, the United States of America, the European Union, the United Kingdom, or other relevant sanctions authority
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
name: Acinq
provenance_date: '2026-11-09'
provider_name: Acinq
provider_slug: acinq
slug: acinq-eligibility
source_date: '2026-11-09'
source_filename: acinq-eligibility.yml
source_heading: Eligibility
source_page: https://phoenix.acinq.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Acinq\naid: acinq\nurl: https://phoenix.acinq.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Service is only available to persons in eligible countries. You may not use the Service if you are located\n    in, or a citizen or resident of, any other jurisdiction where ACINQ have determined to prohibit use of the Services\nentity_types:\n- type: individual\n  text: Application is intended for use by persons who are very knowledgeable about cryptocurrency generally and\n    non-custodial wallets in particular.\nrestricted_uses:\n- summary: Sanctioned countries and persons\n\
  \  text: You are not permitted to use any of the Services if (1) you are a in, under the control of, or a national\n    or resident of any country subject to sanctions by the United Nations, the United States of America, the European\n    Union, the United Kingdom, or other relevant sanctions authority\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/acinq/eligibility/acinq-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Acinq's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Blockchain
- Bitcoin
- Lightning Network
- Payments
- Open Source
- Self-Custody
- Node Software
- Cryptocurrency
- Developer Tools
---
