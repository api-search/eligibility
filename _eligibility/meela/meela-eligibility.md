---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: THE SERVICES ARE NOT INTENDED FOR USE IN CONNECTICUT, IDAHO, MAINE, NEVADA, OREGON, UTAH, OR WASHINGTON
  entity_types:
  - text: An Account may be used to arrange Services, including Meela Rides, for another individual, such as a family member.
    type: individual
  minimum_age:
    text: YOU ARE AT LEAST EIGHTEEN (18) YEARS OLD
    value: '18'
  restricted_uses:
  - summary: Not for emergency use
    text: THE SERVICES ARE NOT INTENDED FOR EMERGENCY USE.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Company may also ask you to verify your identity before arranging a ride or making changes to your Account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Meela
provenance_date: '2026-11-10'
provider_name: Meela
provider_slug: meela
slug: meela-eligibility
source_date: '2026-11-10'
source_filename: meela-eligibility.yml
source_heading: Eligibility
source_page: https://www.meela.ai/consumer-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Meela\naid: meela\nurl: https://www.meela.ai/consumer-terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: THE SERVICES ARE NOT INTENDED FOR USE IN CONNECTICUT, IDAHO, MAINE, NEVADA, OREGON, UTAH, OR WASHINGTON\nentity_types:\n- type: individual\n  text: An Account may be used to arrange Services, including Meela Rides, for another individual, such as a family\n    member.\nrestricted_uses:\n- summary: Not for emergency use\n  text: THE SERVICES ARE NOT INTENDED FOR EMERGENCY USE.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ Company may also ask you to verify your identity before arranging a ride or making changes to your Account\nminimum_age:\n  value: '18'\n  text: YOU ARE AT LEAST EIGHTEEN (18) YEARS OLD\n"
source_yaml_url: https://artifacts.apis.io/meela/eligibility/meela-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Meela's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Ai Apps
- Artificial Intelligence
- Voice AI
- AI Companion
- Senior Care
- Elder Care
- Health
- Wellness
- Transportation
---
