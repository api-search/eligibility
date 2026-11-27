---
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - SY
    - KP
    served: []
    text: (i) a national or resident of any country subject to U.S. sanctions or similar restrictions (currently, Cuba, Iran, Syria, North Korea, and the region Crimea)
  entity_types:
  - text: You must be at least 13 years of age or older to use the Services.
    type: individual
  - text: If you use the Services on behalf of a company or other entity then “you” includes you and that entity
    type: business
  minimum_age:
    text: You must be at least 13 years of age or older to use the Services.
    value: '13'
  restricted_uses:
  - summary: Under-13 users barred
    text: Children under the age of 13 are not permitted to use the Services.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Company may require you to provide additional information and documents regarding your use of the Services
excluded_countries:
- CU
- IR
- SY
- KP
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Atrium
provenance_date: '2026-11-09'
provider_name: Atrium
provider_slug: atrium-art
slug: atrium-art-eligibility
source_date: '2026-11-09'
source_filename: atrium-art-eligibility.yml
source_heading: Eligibility
source_page: https://atrium.art/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Atrium\naid: atrium-art\nurl: https://atrium.art/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - SY\n  - KP\n  text: (i) a national or resident of any country subject to U.S. sanctions or similar restrictions (currently,\n    Cuba, Iran, Syria, North Korea, and the region Crimea)\nentity_types:\n- type: individual\n  text: You must be at least 13 years of age or older to use the Services.\n- type: business\n  text: If you use the Services on behalf of a company or other entity then “you” includes you and that entity\nrestricted_uses:\n- summary: Under-13 users barred\n\
  \  text: Children under the age of 13 are not permitted to use the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Company may require you to provide additional information and documents regarding your use of the Services\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years of age or older to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/atrium-art/eligibility/atrium-art-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Atrium's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Digital Health
- Interoperability
---
