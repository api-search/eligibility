---
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - IR
    - KP
    - CU
    - RU
    served: []
    text: Member warrants that it is not located in, and will not use the Services from, any country subject to U.S. or EU trade sanctions (including but not limited to Iran, North Korea, Cuba, and Russia).
  entity_types:
  - text: The Platform and our Services are exclusively available to legal entities and entrepreneurs (as defined in Sec. 14 BGB) and may not be used by consumers
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned countries
    text: Member warrants that it is not located in, and will not use the Services from, any country subject to U.S. or EU trade sanctions
  - summary: No resale
    text: is expressly prohibited from reselling, leasing, distributing or otherwise providing access to the Cloud Services or Third-Party Model Services to any third party.
  - summary: Anthropic model regions
    text: use them outside the regions permitted under the Anthropic Supported Regions Policy
  verification:
    approval_required: true
    kyb: true
    kyc: null
    text: To qualify for admission to the Platform, you must provide certain information as requested in the onboarding process, including but not limited to your name, email address and address, billing information and proof of your entrepreneurial (e.g. VAT ID). We reserve the right to perform a credit check. The Customer has no claim to join as a Member and Blocks reserves the right, in its sole discretion, to decline Customer's application
excluded_countries:
- IR
- KP
- CU
- RU
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Blocks
provenance_date: '2026-11-09'
provider_name: Blocks
provider_slug: blocks
slug: blocks-eligibility
source_date: '2026-11-09'
source_filename: blocks-eligibility.yml
source_heading: Eligibility
source_page: https://blocks.cloud/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Blocks\naid: blocks\nurl: https://blocks.cloud/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - IR\n  - KP\n  - CU\n  - RU\n  text: Member warrants that it is not located in, and will not use the Services from, any country subject to U.S.\n    or EU trade sanctions (including but not limited to Iran, North Korea, Cuba, and Russia).\nentity_types:\n- type: business\n  text: The Platform and our Services are exclusively available to legal entities and entrepreneurs (as defined\n    in Sec. 14 BGB) and may not be used by consumers\nrestricted_uses:\n- summary: Sanctioned countries\n \
  \ text: Member warrants that it is not located in, and will not use the Services from, any country subject to U.S.\n    or EU trade sanctions\n- summary: No resale\n  text: is expressly prohibited from reselling, leasing, distributing or otherwise providing access to the Cloud\n    Services or Third-Party Model Services to any third party.\n- summary: Anthropic model regions\n  text: use them outside the regions permitted under the Anthropic Supported Regions Policy\nverification:\n  kyc: null\n  kyb: true\n  approval_required: true\n  text: To qualify for admission to the Platform, you must provide certain information as requested in the onboarding\n    process, including but not limited to your name, email address and address, billing information and proof of\n    your entrepreneurial (e.g. VAT ID). We reserve the right to perform a credit check. The Customer has no claim\n    to join as a Member and Blocks reserves the right, in its sole discretion, to decline Customer's application\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/blocks/eligibility/blocks-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 6 quoted statements, read from Blocks's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cloud
- Amazon Web Services
- Cost Optimization
- FinOps
- DevOps
- Security
- Artificial Intelligence
---
