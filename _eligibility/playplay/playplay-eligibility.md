---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: subscribing to a PlayPlay offer exclusively intended for professionals
    type: business
  - text: Legal entities must act through a natural person with the legal capacity to contract on behalf of and for the account of the respective legal entity.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctions and export compliance
    text: 'The Customer represents in particular that it: is not a person or entity subject to sanctions imposed by the European Union, the United Kingdom, the United States or the United Nations'
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
name: PlayPlay
provenance_date: '2026-11-10'
provider_name: PlayPlay
provider_slug: playplay
slug: playplay-eligibility
source_date: '2026-11-10'
source_filename: playplay-eligibility.yml
source_heading: Eligibility
source_page: https://playplay.com/legal-information
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PlayPlay\naid: playplay\nurl: https://playplay.com/legal-information\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: subscribing to a PlayPlay offer exclusively intended for professionals\n- type: business\n  text: Legal entities must act through a natural person with the legal capacity to contract on behalf of and for\n    the account of the respective legal entity.\nrestricted_uses:\n- summary: Sanctions and export compliance\n  text: 'The Customer represents in particular that it: is not a person or entity subject\
  \ to sanctions imposed by\n    the European Union, the United Kingdom, the United States or the United Nations'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/playplay/eligibility/playplay-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from PlayPlay's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Video
- Video Creation
- Content Creation
- Marketing
- Media
- Software-as-a-Service
- Artificial Intelligence
- No-Code
---
