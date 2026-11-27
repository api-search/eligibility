---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This Site is intended for and applicable only for residents of the United States.
  minimum_age:
    text: Starry does not permit individuals under the age of 13 to register an account on our Site.
    value: '13'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Verification of information may be required prior to the acknowledgment or completion of any transaction.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Starry
provenance_date: '2026-11-10'
provider_name: Starry
provider_slug: starry
slug: starry-eligibility
source_date: '2026-11-10'
source_filename: starry-eligibility.yml
source_heading: Eligibility
source_page: https://starry.com/legal/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Starry\naid: starry\nurl: https://starry.com/legal/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This Site is intended for and applicable only for residents of the United States.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Verification of information may be required prior to the acknowledgment or completion of any transaction.\nminimum_age:\n  value: '13'\n  text: Starry does not permit individuals under the age of 13 to register an account on our Site.\n"
source_yaml_url: https://artifacts.apis.io/starry/eligibility/starry-eligibility.yml
stated_fields:
- countries
- verification
- minimum_age
summary_line: 3 quoted statements, read from Starry's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Internet Service Provider
- Broadband
- Fixed Wireless
- Telecommunications
- Networking
- Consumer Internet
- Millimeter Wave
---
