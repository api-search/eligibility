---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are only available to the residents of the U.S.A.
  entity_types:
  - text: The Waffle Products are intended for your personal use.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful purposes only
    text: you will use and access the Waffle Products for lawful purposes only.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: You hereby authorize Waffle, directly or through third parties, to make any inquiries we consider necessary to validate your identity and/or authenticate your identity and account information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Waffle Labs
provenance_date: '2026-11-10'
provider_name: Waffle Labs
provider_slug: trywaffle-com
slug: trywaffle-com-eligibility
source_date: '2026-11-10'
source_filename: trywaffle-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.waffleinsurance.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Waffle Labs\naid: trywaffle-com\nurl: https://www.waffleinsurance.com/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are only available to the residents of the U.S.A.\nentity_types:\n- type: individual\n  text: The Waffle Products are intended for your personal use.\nrestricted_uses:\n- summary: Lawful purposes only\n  text: you will use and access the Waffle Products for lawful purposes only.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: You hereby authorize Waffle, directly or through third parties, to make any\
  \ inquiries we consider necessary\n    to validate your identity and/or authenticate your identity and account information.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/trywaffle-com/eligibility/trywaffle-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Waffle Labs's own page on 2026-11-10.
synthetic: false
tags:
- Insurance
- Fintech
- Software-as-a-Service
- Consumer
---
