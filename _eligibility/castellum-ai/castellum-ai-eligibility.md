---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: User is an individual or entity that desires to use Castellum.AI’s technology
    type: individual
  - text: User is an individual or entity that desires to use Castellum.AI’s technology
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: User agrees not to export or re-export any Product or accompanying documentation in violation of any applicable laws and regulations of the United States
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
name: Castellum.AI
provenance_date: '2026-11-09'
provider_name: Castellum.AI
provider_slug: castellum-ai
slug: castellum-ai-eligibility
source_date: '2026-11-09'
source_filename: castellum-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.castellum.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Castellum.AI\naid: castellum-ai\nurl: https://www.castellum.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: User is an individual or entity that desires to use Castellum.AI’s technology\n- type: business\n  text: User is an individual or entity that desires to use Castellum.AI’s technology\nrestricted_uses:\n- summary: Export restrictions\n  text: User agrees not to export or re-export any Product or accompanying documentation in violation of any applicable\n    laws and regulations of the United States\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/castellum-ai/eligibility/castellum-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Castellum.AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AML
- KYC
- Fintech
- Compliance
- Artificial Intelligence
---
