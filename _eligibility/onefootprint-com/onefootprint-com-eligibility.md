---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Services only if you are 18 years or older and capable of forming a binding contract with One Footprint
    type: individual
  - text: If you are accessing and using the Services on behalf of a company (such as your employer) or other legal entity, you represent and warrant that you have the authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: You may use the Services only if you are 18 years or older
    value: '18'
  restricted_uses:
  - summary: Sanctioned countries and parties
    text: you are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a terrorist-supporting country; and (ii) you are not listed on any U.S. Government list of prohibited or restricted parties.
  - summary: Prohibited content and conduct
    text: 'Post, upload, publish, submit or transmit any User Content that: (i) infringes, misappropriates or violates a third party’s patent, copyright, trademark, trade secret, moral rights or other intellectual property rights'
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
name: Footprint
provenance_date: '2026-11-10'
provider_name: Footprint
provider_slug: onefootprint-com
slug: onefootprint-com-eligibility
source_date: '2026-11-10'
source_filename: onefootprint-com-eligibility.yml
source_heading: Eligibility
source_page: https://onefootprint.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Footprint\naid: onefootprint-com\nurl: https://onefootprint.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Services only if you are 18 years or older and capable of forming a binding contract with\n    One Footprint\n- type: business\n  text: If you are accessing and using the Services on behalf of a company (such as your employer) or other legal\n    entity, you represent and warrant that you have the authority to bind that entity to these Terms.\nrestricted_uses:\n- summary: Sanctioned countries\
  \ and parties\n  text: you are not located in a country that is subject to a U.S. Government embargo, or that has been designated\n    by the U.S. Government as a terrorist-supporting country; and (ii) you are not listed on any U.S. Government\n    list of prohibited or restricted parties.\n- summary: Prohibited content and conduct\n  text: 'Post, upload, publish, submit or transmit any User Content that: (i) infringes, misappropriates or violates\n    a third party’s patent, copyright, trademark, trade secret, moral rights or other intellectual property rights'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may use the Services only if you are 18 years or older\n"
source_yaml_url: https://artifacts.apis.io/onefootprint-com/eligibility/onefootprint-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Footprint's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Risk Management
- ESG
- Sustainability
---
