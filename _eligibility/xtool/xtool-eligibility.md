---
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: 'Sanctioned Country/Region, including without limitation: Cuba, Iran, North Korea, Syria, the Crimea region'
  entity_types:
  - text: (i) you are at least 18 years old, and (ii) you are legally able to enter into contracts under Applicable Law.
    type: individual
  - text: If you use the Service on behalf of a business, you confirm that you are authorized to bind that business to this Agreement.
    type: business
  minimum_age:
    text: The Service is available only to individuals aged 18 or older (or the local minimum age), unless used with a parent or guardian.
    value: '18'
  restricted_uses:
  - summary: Civilian consumer use only
    text: Our products and services are consumer products intended for lawful civilian use only
  - summary: No military, defense or weapons use
    text: for any military, defense, weapons, or other prohibited purpose, including design, development, manufacture, testing, or use of weapons or weapons systems.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: xTool
provenance_date: '2026-11-10'
provider_name: xTool
provider_slug: xtool
slug: xtool-eligibility
source_date: '2026-11-10'
source_filename: xtool-eligibility.yml
source_heading: Eligibility
source_page: https://www.xtool.com/pages/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: xTool\naid: xtool\nurl: https://www.xtool.com/pages/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: 'Sanctioned Country/Region, including without limitation: Cuba, Iran, North Korea, Syria, the Crimea region'\nentity_types:\n- type: individual\n  text: (i) you are at least 18 years old, and (ii) you are legally able to enter into contracts under Applicable\n    Law.\n- type: business\n  text: If you use the Service on behalf of a business, you confirm that you are authorized to bind that business\n    to this Agreement.\nrestricted_uses:\n\
  - summary: Civilian consumer use only\n  text: Our products and services are consumer products intended for lawful civilian use only\n- summary: No military, defense or weapons use\n  text: for any military, defense, weapons, or other prohibited purpose, including design, development, manufacture,\n    testing, or use of weapons or weapons systems.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Service is available only to individuals aged 18 or older (or the local minimum age), unless used with\n    a parent or guardian.\n"
source_yaml_url: https://artifacts.apis.io/xtool/eligibility/xtool-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from xTool's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Technology
- Hardware
- Laser Engraving
- Laser Cutting
- Digital Fabrication
- Manufacturing
- Maker
---
