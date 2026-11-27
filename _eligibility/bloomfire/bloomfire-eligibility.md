---
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: Subscribers shall not permit Members to access or use the Bloomfire Service or any User Content in a U.S.-embargoed country (currently Cuba, Iran, North Korea, Sudan or Syria)
  entity_types:
  - text: You are 18 years old or older.
    type: individual
  - text: If you are subscribing to the Bloomfire Service within the scope of your contract or employment with an entity (e.g., a corporation, limited liability company, or partnership), (a) you represent that you have the authority to bind that entity to these Terms of Use
    type: business
  - text: If you are accepting these Terms of Use for end use by any agency of the U.S. federal government, your use is governed solely by the following
    type: government
  minimum_age:
    text: You are 18 years old or older.
    value: '18'
  restricted_uses:
  - summary: Direct competitors barred
    text: you may not use the Bloomfire Service if you are or are employed by a direct competitor of Bloomfire.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bloomfire
provenance_date: '2026-11-09'
provider_name: Bloomfire
provider_slug: bloomfire
slug: bloomfire-eligibility
source_date: '2026-11-09'
source_filename: bloomfire-eligibility.yml
source_heading: Eligibility
source_page: https://bloomfire.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bloomfire\naid: bloomfire\nurl: https://bloomfire.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: Subscribers shall not permit Members to access or use the Bloomfire Service or any User Content in a U.S.-embargoed\n    country (currently Cuba, Iran, North Korea, Sudan or Syria)\nentity_types:\n- type: individual\n  text: You are 18 years old or older.\n- type: business\n  text: If you are subscribing to the Bloomfire Service within the scope of your contract or employment with an\n    entity (e.g., a corporation, limited liability\
  \ company, or partnership), (a) you represent that you have the\n    authority to bind that entity to these Terms of Use\n- type: government\n  text: If you are accepting these Terms of Use for end use by any agency of the U.S. federal government, your use\n    is governed solely by the following\nrestricted_uses:\n- summary: Direct competitors barred\n  text: you may not use the Bloomfire Service if you are or are employed by a direct competitor of Bloomfire.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are 18 years old or older.\n"
source_yaml_url: https://artifacts.apis.io/bloomfire/eligibility/bloomfire-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Bloomfire's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Knowledge Management
- Enterprise
- Platform
- API-First
---
