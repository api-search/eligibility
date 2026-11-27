---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: Our Website and our Apps are directed to people residing in the United Kingdom.
  entity_types:
  - text: we only provide our Website and Apps for domestic and private use.
    type: individual
  - text: 'If you are a business user:'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No commercial or business use
    text: You agree not to use our Website or Apps for any commercial or business purposes
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
name: Autoura
provenance_date: '2026-11-09'
provider_name: Autoura
provider_slug: autoura
slug: autoura-eligibility
source_date: '2026-11-09'
source_filename: autoura-eligibility.yml
source_heading: Eligibility
source_page: https://www.autoura.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Autoura\naid: autoura\nurl: https://www.autoura.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: Our Website and our Apps are directed to people residing in the United Kingdom.\nentity_types:\n- type: individual\n  text: we only provide our Website and Apps for domestic and private use.\n- type: business\n  text: 'If you are a business user:'\nrestricted_uses:\n- summary: No commercial or business use\n  text: You agree not to use our Website or Apps for any commercial or business purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n \
  \ text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/autoura/eligibility/autoura-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Autoura's own page on 2026-11-09.
synthetic: false
tags:
- Tourism
- Tours
- Travel
- Destination
- Experience
- Digital Tourism
---
