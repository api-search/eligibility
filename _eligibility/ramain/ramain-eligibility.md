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
    text: you are not located in, or a national or resident of, a country or territory subject to comprehensive U.S. government embargo (currently including Cuba, Iran, North Korea, Syria, and the Crimea, Donetsk, and Luhansk regions of Ukraine)
  entity_types:
  - text: If you use the Service on behalf of a company or other legal entity, you represent and warrant that you have authority to bind that entity to these Terms.
    type: individual
  - text: You are using the Service on behalf of a business, in each case as modified by these Terms.
    type: business
  minimum_age:
    text: be at least 18 years of age, or the age of majority in your jurisdiction if higher
    value: '18'
  restricted_uses:
  - summary: High-impact regulated contexts
    text: The Service is a general-purpose AI tool. It is not designed or validated for use in life-critical, safety-critical, legally determinative, or other high-impact contexts without appropriate human oversight and professional review.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: RamAIn reserves the right to verify eligibility and to refuse or terminate access where eligibility requirements are not met.
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
name: RamAIn
provenance_date: '2026-11-10'
provider_name: RamAIn
provider_slug: ramain
slug: ramain-eligibility
source_date: '2026-11-10'
source_filename: ramain-eligibility.yml
source_heading: Eligibility
source_page: https://ramain.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RamAIn\naid: ramain\nurl: https://ramain.ai/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: you are not located in, or a national or resident of, a country or territory subject to comprehensive U.S.\n    government embargo (currently including Cuba, Iran, North Korea, Syria, and the Crimea, Donetsk, and Luhansk\n    regions of Ukraine)\nentity_types:\n- type: individual\n  text: If you use the Service on behalf of a company or other legal entity, you represent and warrant that you\n    have authority to bind that entity to these Terms.\n- type:\
  \ business\n  text: You are using the Service on behalf of a business, in each case as modified by these Terms.\nrestricted_uses:\n- summary: High-impact regulated contexts\n  text: The Service is a general-purpose AI tool. It is not designed or validated for use in life-critical, safety-critical,\n    legally determinative, or other high-impact contexts without appropriate human oversight and professional review.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: RamAIn reserves the right to verify eligibility and to refuse or terminate access where eligibility requirements\n    are not met.\nminimum_age:\n  value: '18'\n  text: be at least 18 years of age, or the age of majority in your jurisdiction if higher\n"
source_yaml_url: https://artifacts.apis.io/ramain/eligibility/ramain-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from RamAIn's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Automation
- RPA
- Computer Use
- Workflow Automation
- UI Automation
---
