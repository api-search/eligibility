---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served:
    - US
    text: '"Territory” means the United States. Export compliance: (a) it is not located in, and will not use the Subscription Services from, any country subject to U.S. export restrictions (currently including Cuba, Iran, North Korea, Sudan, Syria, and Crimea Region)'
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk activities
    text: The Subscription Services are not designed for any purpose requiring fail-safe performance, including stock trading, financial transaction processing, operation of nuclear facilities, aircraft navigation or communication systems, air traffic control
  - summary: Nuclear, chemical, biological weapons, rockets, UAV systems
    text: Customer will not use the Subscription Services in the design, development, or production of nuclear, chemical, or biological weapons, or rocket systems, space launch vehicles, sounding rockets, or unmanned air vehicle systems
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Customer must register for an account. When Customer registers for an account, Customer will be required to provide certain identifying information
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
name: CeresAI
provenance_date: '2026-11-09'
provider_name: CeresAI
provider_slug: ceresai
slug: ceresai-eligibility
source_date: '2026-11-09'
source_filename: ceresai-eligibility.yml
source_heading: Eligibility
source_page: https://ceres.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CeresAI\naid: ceresai\nurl: https://ceres.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: '\"Territory” means the United States. Export compliance: (a) it is not located in, and will not use the\n    Subscription Services from, any country subject to U.S. export restrictions (currently including Cuba, Iran,\n    North Korea, Sudan, Syria, and Crimea Region)'\nentity_types: []\nrestricted_uses:\n- summary: High-risk activities\n  text: The Subscription Services are not designed for any purpose requiring fail-safe performance,\
  \ including stock\n    trading, financial transaction processing, operation of nuclear facilities, aircraft navigation or communication\n    systems, air traffic control\n- summary: Nuclear, chemical, biological weapons, rockets, UAV systems\n  text: Customer will not use the Subscription Services in the design, development, or production of nuclear, chemical,\n    or biological weapons, or rocket systems, space launch vehicles, sounding rockets, or unmanned air vehicle systems\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Customer must register for an account. When Customer registers for an account, Customer will be required\n    to provide certain identifying information\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ceresai/eligibility/ceresai-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 4 quoted statements, read from CeresAI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Agriculture
- AgTech
- Geospatial
- Remote Sensing
- Satellite Imagery
- Machine Learning
- Crop Health
- Agricultural Intelligence
- Insurance
---
