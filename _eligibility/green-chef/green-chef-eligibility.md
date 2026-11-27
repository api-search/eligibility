---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: intended for use by individuals in the contiguous United States of America, excluding Alaska, Hawaii, Puerto Rico, and other U.S. Territories
  entity_types:
  - text: 'you represent and warrant that you: (1) are legally capable of entering into these Terms; (2) are at least 18 years old'
    type: individual
  minimum_age:
    text: (2) are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Personal, non-commercial use of Materials
    text: Green Chef grants you a limited revocable, non-exclusive license to use the Materials solely in order to utilize Green Chef’s Offerings for personal, non-commercial use.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: As a part of the verification process, Green Chef may require you to provide additional identification information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Green Chef
provenance_date: '2026-11-09'
provider_name: Green Chef
provider_slug: green-chef
slug: green-chef-eligibility
source_date: '2026-11-09'
source_filename: green-chef-eligibility.yml
source_heading: Eligibility
source_page: https://www.greenchef.com:443/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Green Chef\naid: green-chef\nurl: https://www.greenchef.com:443/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: intended for use by individuals in the contiguous United States of America, excluding Alaska, Hawaii, Puerto\n    Rico, and other U.S. Territories\nentity_types:\n- type: individual\n  text: 'you represent and warrant that you: (1) are legally capable of entering into these Terms; (2) are at least\n    18 years old'\nrestricted_uses:\n- summary: Personal, non-commercial use of Materials\n  text: Green Chef grants you a limited revocable, non-exclusive\
  \ license to use the Materials solely in order to\n    utilize Green Chef’s Offerings for personal, non-commercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: As a part of the verification process, Green Chef may require you to provide additional identification information.\nminimum_age:\n  value: '18'\n  text: (2) are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/green-chef/eligibility/green-chef-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Green Chef's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Meal Kit
- Organic
- Sustainability
- Food
---
