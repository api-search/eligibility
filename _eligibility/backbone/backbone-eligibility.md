---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that (i) you are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a terrorist-supporting country
  entity_types:
  - text: You may use the Services only if you are 13 years or older, capable of forming a binding contract with Backbone, and not barred from using the Services under applicable law.
    type: individual
  minimum_age:
    text: You may use the Services only if you are 13 years or older
    value: '13'
  restricted_uses:
  - summary: Prohibited content and conduct
    text: 'Post, upload, publish, submit, or transmit any Content that: (i) infringes, misappropriates, or violates a third party’s patent, copyright, trademark, trade secret, moral rights, or other intellectual property rights'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may need to provide additional information to verify your identity before completing your Order
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Backbone
provenance_date: '2026-11-09'
provider_name: Backbone
provider_slug: backbone
slug: backbone-eligibility
source_date: '2026-11-09'
source_filename: backbone-eligibility.yml
source_heading: Eligibility
source_page: https://backbone.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Backbone\naid: backbone\nurl: https://backbone.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that (i) you are not located in a country that is subject to a U.S. Government\n    embargo, or that has been designated by the U.S. Government as a terrorist-supporting country\nentity_types:\n- type: individual\n  text: You may use the Services only if you are 13 years or older, capable of forming a binding contract with Backbone,\n    and not barred from using the Services under applicable law.\nrestricted_uses:\n\
  - summary: Prohibited content and conduct\n  text: 'Post, upload, publish, submit, or transmit any Content that: (i) infringes, misappropriates, or violates\n    a third party’s patent, copyright, trademark, trade secret, moral rights, or other intellectual property rights'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may need to provide additional information to verify your identity before completing your Order\nminimum_age:\n  value: '13'\n  text: You may use the Services only if you are 13 years or older\n"
source_yaml_url: https://artifacts.apis.io/backbone/eligibility/backbone-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Backbone's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Entertainment
- Gaming
- Mobile Gaming
- Gaming Controller
- Consumer Electronics
- Hardware
- E-Commerce
---
