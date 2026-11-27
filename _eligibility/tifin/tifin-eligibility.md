---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - RU
    - SY
    served: []
    text: including without limitation Cuba, Iran, North Korea, Russia, Syria, and the Crimea Donetsk and Luhansk regions of Ukraine
  entity_types:
  - text: are an individual, legal person or other organization with full legal capacity and authority to enter into these Terms and Conditions
    type: individual
  minimum_age:
    text: are at least 18 years of age or of legal age to form a binding contract under applicable law
    value: '18'
  restricted_uses:
  - summary: Sanctioned or denied persons barred
    text: 'You are prohibited from accessing or using the Services, or registering for an Account, if you: (1) have been identified as a “Specially Designated National” by the Office of Foreign Assets Control'
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: You hereby authorize the Company Group, directly or through third parties, to make any inquiries we deem necessary to verify your identity
excluded_countries:
- CU
- IR
- KP
- RU
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: TIFIN
provenance_date: '2026-11-10'
provider_name: TIFIN
provider_slug: tifin
slug: tifin-eligibility
source_date: '2026-11-10'
source_filename: tifin-eligibility.yml
source_heading: Eligibility
source_page: https://tifin.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TIFIN\naid: tifin\nurl: https://tifin.com/terms-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - RU\n  - SY\n  text: including without limitation Cuba, Iran, North Korea, Russia, Syria, and the Crimea Donetsk and Luhansk\n    regions of Ukraine\nentity_types:\n- type: individual\n  text: are an individual, legal person or other organization with full legal capacity and authority to enter into\n    these Terms and Conditions\nrestricted_uses:\n- summary: Sanctioned or denied persons barred\n  text: 'You are prohibited from accessing or\
  \ using the Services, or registering for an Account, if you: (1) have\n    been identified as a “Specially Designated National” by the Office of Foreign Assets Control'\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: You hereby authorize the Company Group, directly or through third parties, to make any inquiries we deem\n    necessary to verify your identity\nminimum_age:\n  value: '18'\n  text: are at least 18 years of age or of legal age to form a binding contract under applicable law\n"
source_yaml_url: https://artifacts.apis.io/tifin/eligibility/tifin-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from TIFIN's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Services
- Wealth Management
- Asset Management
- Artificial Intelligence
- Fintech
- WealthTech
- Financial Advisors
- Investment Management
- Insurance
---
