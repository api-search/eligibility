---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a terrorist-supporting country
  entity_types:
  - text: You may use the Services only if you are at least 13 years of age
    type: individual
  minimum_age:
    text: You may use the Services only if you are at least 13 years of age (or such other minimum age at which you can provide consent to data processing under the laws of your territory)
    value: '13'
  restricted_uses:
  - summary: Prohibited content and conduct
    text: 'Post, upload, publish, submit or transmit any User Content that: (i) infringes, misappropriates or violates a third party''s patent, copyright, trademark, trade secret, moral rights or other intellectual property rights'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may need to provide additional information to verify your identity before completing your Transaction
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Voxer
provenance_date: '2026-11-10'
provider_name: Voxer
provider_slug: voxer
slug: voxer-eligibility
source_date: '2026-11-10'
source_filename: voxer-eligibility.yml
source_heading: Eligibility
source_page: https://www.voxer.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Voxer\naid: voxer\nurl: https://www.voxer.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you are not located in a country that is subject to a U.S. Government embargo,\n    or that has been designated by the U.S. Government as a terrorist-supporting country\nentity_types:\n- type: individual\n  text: You may use the Services only if you are at least 13 years of age\nrestricted_uses:\n- summary: Prohibited content and conduct\n  text: 'Post, upload, publish, submit or transmit any User Content that: (i) infringes, misappropriates or violates\n\
  \    a third party''s patent, copyright, trademark, trade secret, moral rights or other intellectual property rights'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may need to provide additional information to verify your identity before completing your Transaction\nminimum_age:\n  value: '13'\n  text: You may use the Services only if you are at least 13 years of age (or such other minimum age at which you\n    can provide consent to data processing under the laws of your territory)\n"
source_yaml_url: https://artifacts.apis.io/voxer/eligibility/voxer-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Voxer's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Communications
- Push To Talk
- Walkie-Talkie
- Voice
- Messaging
- Mobile
- SDK
---
