---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Not all products and services featured in this Site are available in all geographic areas.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unauthorized access
    text: Unauthorized use of, or entry into, this Site, or the misuse of passwords or information contained within this Site, is strictly prohibited.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Your eligibility for particular products and services is subject to final acceptance by Santander or the third-party providers, as applicable.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Santander US
provenance_date: '2026-11-10'
provider_name: Santander US
provider_slug: santander-us
slug: santander-us-eligibility
source_date: '2026-11-10'
source_filename: santander-us-eligibility.yml
source_heading: Eligibility
source_page: https://www.santanderbank.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Santander US\naid: santander-us\nurl: https://www.santanderbank.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Not all products and services featured in this Site are available in all geographic areas.\nentity_types: []\nrestricted_uses:\n- summary: Unauthorized access\n  text: Unauthorized use of, or entry into, this Site, or the misuse of passwords or information contained within\n    this Site, is strictly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Your eligibility for particular products and services is subject\
  \ to final acceptance by Santander or the\n    third-party providers, as applicable.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/santander-us/eligibility/santander-us-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Santander US's own page on 2026-11-10.
synthetic: false
tags:
- Financial Services
- Banking
- United States
- Super-Regional Bank
- Consumer Banking
- Open Finance
---
