---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The ability to purchase products and services may vary based on your location, and such restrictions may change without notice.
  entity_types:
  - text: The Platform is intended for use by adults. Any use by anyone under eighteen (18) years of age must be with the full permission of their parent/legal guardian who accepts all Terms contained herein on behalf of such minor.
    type: individual
  minimum_age:
    text: The Platform is intended for use by adults. Any use by anyone under eighteen (18) years of age must be with the full permission of their parent/legal guardian
    value: '18'
  restricted_uses:
  - summary: Unlawful or fraudulent use
    text: you will not use any electronic communication feature of the Platform for any purpose that is unlawful or in violation of these Terms
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Verification of information may be required prior to the acknowledgment or completion of any transaction.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Feastables
provenance_date: '2026-11-09'
provider_name: Feastables
provider_slug: feastables
slug: feastables-eligibility
source_date: '2026-11-09'
source_filename: feastables-eligibility.yml
source_heading: Eligibility
source_page: https://feastables.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Feastables\naid: feastables\nurl: https://feastables.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The ability to purchase products and services may vary based on your location, and such restrictions may\n    change without notice.\nentity_types:\n- type: individual\n  text: The Platform is intended for use by adults. Any use by anyone under eighteen (18) years of age must be with\n    the full permission of their parent/legal guardian who accepts all Terms contained herein on behalf of such\n    minor.\nrestricted_uses:\n- summary: Unlawful or fraudulent\
  \ use\n  text: you will not use any electronic communication feature of the Platform for any purpose that is unlawful or\n    in violation of these Terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Verification of information may be required prior to the acknowledgment or completion of any transaction.\nminimum_age:\n  value: '18'\n  text: The Platform is intended for use by adults. Any use by anyone under eighteen (18) years of age must be with\n    the full permission of their parent/legal guardian\n"
source_yaml_url: https://artifacts.apis.io/feastables/eligibility/feastables-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Feastables's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer Packaged Goods
- Food and Beverage
- Chocolate
- E-Commerce
- Retail
- Agentic Commerce
- MCP
- Universal Commerce Protocol
- Shopify
---
