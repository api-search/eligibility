---
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - US
    served: []
    text: you are not a US citizen or resident (unless you are or represent a corporate undertaking that is regulated in the USA at federal or state level to provide services materially the same as those which we provide).
  entity_types:
  - text: you are at least 18 years old, or such older minimum legal age to use the Services as determined by the laws of the country in which you are resident and have full capacity
    type: individual
  - text: if you act on behalf of a corporate undertaking, you are duly authorised to act on its behalf
    type: business
  minimum_age:
    text: you are at least 18 years old, or such older minimum legal age to use the Services as determined by the laws of the country in which you are resident and have full capacity
    value: '18'
  restricted_uses:
  - summary: Unlawful activity
    text: You agree not to use the Services for any unlawful activity
  - summary: Restricted territories
    text: you are not a resident in any Restricted Territories
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
name: Covercy
provenance_date: '2026-11-09'
provider_name: Covercy
provider_slug: covercy
slug: covercy-eligibility
source_date: '2026-11-09'
source_filename: covercy-eligibility.yml
source_heading: Eligibility
source_page: https://www.covercy.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Covercy\naid: covercy\nurl: https://www.covercy.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - US\n  text: you are not a US citizen or resident (unless you are or represent a corporate undertaking that is regulated\n    in the USA at federal or state level to provide services materially the same as those which we provide).\nentity_types:\n- type: individual\n  text: you are at least 18 years old, or such older minimum legal age to use the Services as determined by the\n    laws of the country in which you are resident and have full capacity\n- type: business\n\
  \  text: if you act on behalf of a corporate undertaking, you are duly authorised to act on its behalf\nrestricted_uses:\n- summary: Unlawful activity\n  text: You agree not to use the Services for any unlawful activity\n- summary: Restricted territories\n  text: you are not a resident in any Restricted Territories\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old, or such older minimum legal age to use the Services as determined by the\n    laws of the country in which you are resident and have full capacity\n"
source_yaml_url: https://artifacts.apis.io/covercy/eligibility/covercy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Covercy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- Investment Management
- Fund Administration
- Investor Relations
- Payments
- Fintech
- Capital Raising
---
