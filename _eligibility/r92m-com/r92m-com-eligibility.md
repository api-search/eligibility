---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Route 92 Medical reserves the right to limit, in its sole discretion, the availability of any product to any person or geographic area. Not all products are available outside the United States.
  entity_types:
  - text: You are at least 18 years of age
    type: individual
  - text: Enter into this agreement on behalf of another person or entity without consent or the legal capacity to make such agreements as a representative of an organization or entity
    type: other
  minimum_age:
    text: You are at least 18 years of age; this Website is not intended to be directed to children.
    value: '18'
  restricted_uses:
  - summary: Unlawful use
    text: You use the Website and Services according to these Terms of Use and all applicable laws and regulations determined by the state and country of your residence
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
name: R92m
provenance_date: '2026-11-10'
provider_name: R92m
provider_slug: r92m-com
slug: r92m-com-eligibility
source_date: '2026-11-10'
source_filename: r92m-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.route92medical.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: R92m\naid: r92m-com\nurl: https://www.route92medical.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Route 92 Medical reserves the right to limit, in its sole discretion, the availability of any product to\n    any person or geographic area. Not all products are available outside the United States.\nentity_types:\n- type: individual\n  text: You are at least 18 years of age\n- type: other\n  text: Enter into this agreement on behalf of another person or entity without consent or the legal capacity to\n    make such agreements as a representative of an organization\
  \ or entity\nrestricted_uses:\n- summary: Unlawful use\n  text: You use the Website and Services according to these Terms of Use and all applicable laws and regulations\n    determined by the state and country of your residence\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least 18 years of age; this Website is not intended to be directed to children.\n"
source_yaml_url: https://artifacts.apis.io/r92m-com/eligibility/r92m-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from R92m's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Technology
- Platform
- Medical
---
