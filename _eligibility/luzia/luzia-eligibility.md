---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - BY
    - KP
    - CU
    - IR
    - RU
    - SY
    - SD
    - UA
    - VE
    served: []
    text: The availability of access and use has no territorial limitation except for Belarus, North Korea, Cuba, Iran, Russia, Syria, Sudan, Ukraine, Venezuela.
  entity_types:
  - text: Users over 13 years of age if you reside in any LATAM country, or 14 years of age if you reside in any European country.
    type: individual
  minimum_age:
    text: The use of this application is solely and exclusively intended for Users over 13 years of age if you reside in any LATAM country, or 14 years of age if you reside in any European country.
    value: 13 (LATAM) / 14 (Europe)
  restricted_uses:
  - summary: Illegal or harmful content
    text: Sharing, distributing or soliciting illegal content, including but not limited to material that promotes violence, child exploitation, abuse, human trafficking or any criminal activity is prohibited.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: LUZIA may also implement verification systems to ensure the authenticity of users and the security of the platform. Such systems may include, among others, authentication processes, identity validation and activity analysis
excluded_countries:
- BY
- KP
- CU
- IR
- RU
- SY
- SD
- UA
- VE
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Luzia
provenance_date: '2026-11-10'
provider_name: Luzia
provider_slug: luzia
slug: luzia-eligibility
source_date: '2026-11-10'
source_filename: luzia-eligibility.yml
source_heading: Eligibility
source_page: https://www.luzia.com/en/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Luzia\naid: luzia\nurl: https://www.luzia.com/en/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - BY\n  - KP\n  - CU\n  - IR\n  - RU\n  - SY\n  - SD\n  - UA\n  - VE\n  text: The availability of access and use has no territorial limitation except for Belarus, North Korea, Cuba,\n    Iran, Russia, Syria, Sudan, Ukraine, Venezuela.\nentity_types:\n- type: individual\n  text: Users over 13 years of age if you reside in any LATAM country, or 14 years of age if you reside in any European\n    country.\nrestricted_uses:\n- summary: Illegal or harmful content\n  text: Sharing,\
  \ distributing or soliciting illegal content, including but not limited to material that promotes\n    violence, child exploitation, abuse, human trafficking or any criminal activity is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: LUZIA may also implement verification systems to ensure the authenticity of users and the security of the\n    platform. Such systems may include, among others, authentication processes, identity validation and activity\n    analysis\nminimum_age:\n  value: 13 (LATAM) / 14 (Europe)\n  text: The use of this application is solely and exclusively intended for Users over 13 years of age if you reside\n    in any LATAM country, or 14 years of age if you reside in any European country.\n"
source_yaml_url: https://artifacts.apis.io/luzia/eligibility/luzia-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Luzia's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Assistant
- Chatbots
- Consumer
- Image Generation
- WhatsApp
---
