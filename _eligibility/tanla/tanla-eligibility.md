---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: This Website is controlled, operated and administered by Tanla from its offices within India. Any access to this Website from territories where its content is illegal, is prohibited.
  entity_types:
  - text: You confirm that you are (1) of majority age as under Indian laws; and (2) not already restricted by us or otherwise under any applicable laws from using the Website.
    type: individual
  minimum_age:
    text: You confirm that you are (1) of majority age as under Indian laws
    value: majority age under Indian laws
  restricted_uses:
  - summary: Unlawful purposes
    text: You shall not use the Website for any purpose(s) that is unlawful or prohibited by the Terms of Use and / or under any applicable laws.
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
name: Tanla
provenance_date: '2026-11-10'
provider_name: Tanla
provider_slug: tanla
slug: tanla-eligibility
source_date: '2026-11-10'
source_filename: tanla-eligibility.yml
source_heading: Eligibility
source_page: https://www.tanla.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tanla\naid: tanla\nurl: https://www.tanla.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: This Website is controlled, operated and administered by Tanla from its offices within India. Any access\n    to this Website from territories where its content is illegal, is prohibited.\nentity_types:\n- type: individual\n  text: You confirm that you are (1) of majority age as under Indian laws; and (2) not already restricted by us\n    or otherwise under any applicable laws from using the Website.\nrestricted_uses:\n- summary: Unlawful purposes\n  text: You shall\
  \ not use the Website for any purpose(s) that is unlawful or prohibited by the Terms of Use and\n    / or under any applicable laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: majority age under Indian laws\n  text: You confirm that you are (1) of majority age as under Indian laws\n"
source_yaml_url: https://artifacts.apis.io/tanla/eligibility/tanla-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Tanla's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Communications
- Messaging
- Platform
---
