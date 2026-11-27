---
claim_count: 7
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: The Platform is not available in World-Restricted Regions. Any jurisdiction subject to comprehensive sanctions under Singapore, U.S. or EU law (e.g., Cuba, Iran, North Korea, Syria, Crimea, Donetsk, Luhansk).
  entity_types:
  - text: You represent that you are at least 18 years old and have full legal capacity to accept these Terms.
    type: individual
  - text: The Platform is intended solely for personal, non-commercial use.
    type: business
  minimum_age:
    text: You represent that you are at least 18 years old and have full legal capacity to accept these Terms.
    value: '18'
  restricted_uses:
  - summary: No resale of Products
    text: Resale of Products is prohibited unless you have a separate written B2B agreement with Boxo.
  - summary: No money-laundering or sanctions evasion
    text: The Platform must not be used to facilitate money-laundering, terrorist financing, sanctions evasion or other illegal conduct.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Boxo may request additional KYC information (photo ID, selfie, proof of address) to satisfy AML/CFT obligations.
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
name: Appboxo
provenance_date: '2026-11-09'
provider_name: Appboxo
provider_slug: appboxo
slug: appboxo-eligibility
source_date: '2026-11-09'
source_filename: appboxo-eligibility.yml
source_heading: Eligibility
source_page: https://www.boxo.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Appboxo\naid: appboxo\nurl: https://www.boxo.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: The Platform is not available in World-Restricted Regions. Any jurisdiction subject to comprehensive sanctions\n    under Singapore, U.S. or EU law (e.g., Cuba, Iran, North Korea, Syria, Crimea, Donetsk, Luhansk).\nentity_types:\n- type: individual\n  text: You represent that you are at least 18 years old and have full legal capacity to accept these Terms.\n- type: business\n  text: The Platform is intended solely for personal, non-commercial use.\nrestricted_uses:\n\
  - summary: No resale of Products\n  text: Resale of Products is prohibited unless you have a separate written B2B agreement with Boxo.\n- summary: No money-laundering or sanctions evasion\n  text: The Platform must not be used to facilitate money-laundering, terrorist financing, sanctions evasion or\n    other illegal conduct.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Boxo may request additional KYC information (photo ID, selfie, proof of address) to satisfy AML/CFT obligations.\nminimum_age:\n  value: '18'\n  text: You represent that you are at least 18 years old and have full legal capacity to accept these Terms.\n"
source_yaml_url: https://artifacts.apis.io/appboxo/eligibility/appboxo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Appboxo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Super App
- Mini Apps
- Mobile SDK
- Embedded Finance
- Payments
- SSO
- App Platform
- eSIM
- Developer Tools
---
