---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to register for an Account.
    type: individual
  - text: IF YOU ARE ACCEPTING THESE TERMS ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY
    type: business
  minimum_age:
    text: You must be at least 18 years old to register for an Account.
    value: '18'
  restricted_uses:
  - summary: Export compliance
    text: you must adhere to the applicable export and customs laws and regulations.
  - summary: Unlawful or abusive use
    text: violates or encourages conduct that would violate any criminal laws, any other applicable laws, or any third-party rights.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Arm
provenance_date: '2026-11-09'
provider_name: Arm
provider_slug: arm
slug: arm-eligibility
source_date: '2026-11-09'
source_filename: arm-eligibility.yml
source_heading: Eligibility
source_page: https://www.arm.com/company/policies/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arm\naid: arm\nurl: https://www.arm.com/company/policies/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to register for an Account.\n- type: business\n  text: IF YOU ARE ACCEPTING THESE TERMS ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT YOU HAVE\n    THE AUTHORITY TO BIND SUCH ENTITY\nrestricted_uses:\n- summary: Export compliance\n  text: you must adhere to the applicable export and customs laws and regulations.\n- summary: Unlawful or abusive use\n  text:\
  \ violates or encourages conduct that would violate any criminal laws, any other applicable laws, or any third-party\n    rights.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to register for an Account.\n"
source_yaml_url: https://artifacts.apis.io/arm/eligibility/arm-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Arm's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Semiconductors
- Chip Design
- Processor IP
- Arm Architecture
- Embedded
- Edge AI
- Frontier Tech
---
