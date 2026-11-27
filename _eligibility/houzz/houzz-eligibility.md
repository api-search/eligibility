---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You also represent that you are not (i) located in a country that is subject to a U.S. government embargo, and (ii) listed on any U.S. government list of prohibited or restricted parties.
  entity_types:
  - text: Anyone over 18!
    type: individual
  minimum_age:
    text: Anyone over 18!
    value: '18'
  restricted_uses:
  - summary: Under-18 use prohibited
    text: Use of the Houzz Platform by anyone under 18 years of age is strictly prohibited.
  - summary: Commercial use restricted
    text: your use of the Houzz Platform must be limited to personal non-commercial use.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Additional account requirements, including verification of your account details, may apply depending on your use of the Houzz Platform.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Houzz
provenance_date: '2026-11-09'
provider_name: Houzz
provider_slug: houzz
slug: houzz-eligibility
source_date: '2026-11-09'
source_filename: houzz-eligibility.yml
source_heading: Eligibility
source_page: https://www.houzz.com/termsOfUse
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Houzz\naid: houzz\nurl: https://www.houzz.com/termsOfUse\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: You also represent that you are not (i) located in a country that is subject to a U.S. government embargo,\n    and (ii) listed on any U.S. government list of prohibited or restricted parties.\nentity_types:\n- type: individual\n  text: Anyone over 18!\nrestricted_uses:\n- summary: Under-18 use prohibited\n  text: Use of the Houzz Platform by anyone under 18 years of age is strictly prohibited.\n- summary: Commercial use restricted\n  text: your use of the Houzz\
  \ Platform must be limited to personal non-commercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Additional account requirements, including verification of your account details, may apply depending on\n    your use of the Houzz Platform.\nminimum_age:\n  value: '18'\n  text: Anyone over 18!\n"
source_yaml_url: https://artifacts.apis.io/houzz/eligibility/houzz-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Houzz's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Marketplace
- Home Improvement
- Interior Design
- Home Renovation
- Furniture
- Software-as-a-Service
---
