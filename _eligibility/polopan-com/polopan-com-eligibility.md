---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: servicing shoppers in over 240 countries and territories
  entity_types:
  - text: The Service is intended for individuals who are at least 13 years of age (or at least 16 years of age for residents of the European Economic Area and United Kingdom, unless local law permits a lower age).
    type: individual
  minimum_age:
    text: The Service is intended for individuals who are at least 13 years of age (or at least 16 years of age for residents of the European Economic Area and United Kingdom, unless local law permits a lower age).
    value: '13'
  restricted_uses:
  - summary: Non-commercial personal use only
    text: solely for your personal, non-commercial fashion discovery and shopping purposes
  - summary: Sanctions and export compliance
    text: You represent and warrant that you are not located in, under the control of, or a national or resident of any country or territory subject to comprehensive international trade sanctions or embargoes
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
name: polopan-com
provenance_date: '2026-11-10'
provider_name: polopan-com
provider_slug: polopan-com
slug: polopan-com-eligibility
source_date: '2026-11-10'
source_filename: polopan-com-eligibility.yml
source_heading: Eligibility
source_page: https://polopan.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: polopan-com\naid: polopan-com\nurl: https://polopan.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: servicing shoppers in over 240 countries and territories\nentity_types:\n- type: individual\n  text: The Service is intended for individuals who are at least 13 years of age (or at least 16 years of age for\n    residents of the European Economic Area and United Kingdom, unless local law permits a lower age).\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: solely for your personal, non-commercial fashion discovery and shopping purposes\n- summary:\
  \ Sanctions and export compliance\n  text: You represent and warrant that you are not located in, under the control of, or a national or resident of\n    any country or territory subject to comprehensive international trade sanctions or embargoes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Service is intended for individuals who are at least 13 years of age (or at least 16 years of age for\n    residents of the European Economic Area and United Kingdom, unless local law permits a lower age).\n"
source_yaml_url: https://artifacts.apis.io/polopan-com/eligibility/polopan-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from polopan-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Fashion
- PersonalStylist
- E-Commerce
---
