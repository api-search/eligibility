---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Partner is an independent contractor for all purposes and will be responsible and liable for its own taxes, social contributions, and all other tax related matters.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No use on non-Partner websites
    text: The Partner is not allowed to use the Content on websites that do not belong to the Partner and/or websites that contain inappropriate or unlawful content of any sort.
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
name: Turneo
provenance_date: '2026-11-10'
provider_name: Turneo
provider_slug: turneo
slug: turneo-eligibility
source_date: '2026-11-10'
source_filename: turneo-eligibility.yml
source_heading: Eligibility
source_page: https://www.turneo.com/partner-terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Turneo\naid: turneo\nurl: https://www.turneo.com/partner-terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Partner is an independent contractor for all purposes and will be responsible and liable for its own\n    taxes, social contributions, and all other tax related matters.\nrestricted_uses:\n- summary: No use on non-Partner websites\n  text: The Partner is not allowed to use the Content on websites that do not belong to the Partner and/or websites\n    that contain inappropriate or unlawful content of any sort.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/turneo/eligibility/turneo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Turneo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketplace
- Travel
- Hospitality
- Hotels
- Experience
- Booking
- Activities
- Tours
---
