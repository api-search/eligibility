---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you're a consumer, these terms of use are governed by the law of England and Wales.
    type: individual
  - text: If you're a business user, these terms of use (and any non-contractual obligations arising out of or in connection with them) are governed by the law of England and Wales.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful use only
    text: You may only use our website for lawful purposes and in compliance with all applicable laws.
  - summary: No uploads that are defamatory, fraudulent or illegal
    text: 'You must not upload to our website any content which: is defamatory, obscene, offensive, indecent, malicious, hateful or inflammatory'
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
name: Thames Water
provenance_date: '2026-11-10'
provider_name: Thames Water
provider_slug: thames-water
slug: thames-water-eligibility
source_date: '2026-11-10'
source_filename: thames-water-eligibility.yml
source_heading: Eligibility
source_page: https://www.thameswater.co.uk/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Thames Water\naid: thames-water\nurl: https://www.thameswater.co.uk/legal/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you're a consumer, these terms of use are governed by the law of England and Wales.\n- type: business\n  text: If you're a business user, these terms of use (and any non-contractual obligations arising out of or in\n    connection with them) are governed by the law of England and Wales.\nrestricted_uses:\n- summary: Lawful use only\n  text: You may only use our website for lawful purposes\
  \ and in compliance with all applicable laws.\n- summary: No uploads that are defamatory, fraudulent or illegal\n  text: 'You must not upload to our website any content which: is defamatory, obscene, offensive, indecent, malicious,\n    hateful or inflammatory'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/thames-water/eligibility/thames-water-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Thames Water's own page on 2026-11-10.
synthetic: false
tags:
- Water
- Wastewater
- Utilities
- Billing
- Customer Service
- Business Services
- Property Searches
---
